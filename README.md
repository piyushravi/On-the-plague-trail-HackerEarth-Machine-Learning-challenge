# On the plague trail HackerEarth Machine Learning challenge
I started by visualizing the data against the time spent from the start of 12th July, 2040.
After the visualization of data, it became clear that the number of people infected were closely following an exponential growth with respect to the time spent and only the exponents varied for every region. Then, I used linear regression to find the exponents by taking logarithms of number of people infected until that time. After my first submission I added a few constants in some cases to make the data closer to the actual data to offset the outliers in the traing data which were adversely affecting coefficients obtained from linear regression.
