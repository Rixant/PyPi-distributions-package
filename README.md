# Math_binomial_gaussian_distribution
math_binomial_gaussian_distribution is a python package for dealing with probability distributions calculations in statistics. 

## Contents
1. Binomial Distribution\
  a. calculates mean\
  b. calculates standard deviation\
  c. calculates p and n from the data set\
  d. plots bar chart\
  e. calculates probability density function(p.d.f)\
  f. plots bar chart of p.d.f

2. Gaussian Distribution\
  a. calculates mean\
  b. calculates standard deviation\
  c. plots histogram\
  d. calculates probability density function(p.d.f)\
  e. plots histogram of p.d.f
  
  ## Installation
  Use the package manager [pip](https://pip.pypa.io/en/stable/) to install math_binomial_gaussian_distribution.
  
  ```bash
  pip install math_binomial_gaussian_distribution
  ```
  
 ## Usage
 
 ```python
 from math_binomial_gaussian_distribution import Gaussian, Binomial
 
 Gaussian(20, 3.5) #returns mean and standard deviation
 Gaussian.calculate_mean() #returns mean value
 Gaussian.pdf() #returns probability density function value
 Gaussian.plot_histogram() #plots a histogram of the instance variable data 
 
 Binomial.calculate_stdev() #returns standard deviation value
 Binomial.plot_bar() #plots a bar chart of the instance variable data 
 Binomial.pdf() #returns probability density function value
 Binomial.plot_bar_pdf() #plots a bar chart of pdf
 
 ```
 ## License
[MIT](https://opensource.org/licenses/MIT)
  
  
