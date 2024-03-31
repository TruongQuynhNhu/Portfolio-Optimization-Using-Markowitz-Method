# PortfolioOptimizationUsingMarkowitzMethod

## 1. Installation
(1) install all the necessary package for the project mention infile `requirements.txt`

```
pip install -r requirements.txt
```
(2) run file `PortfolioOptimizationUsingMarkowitzMethod.ipynb`

## 2. Results

![image](https://github.com/TruongQuynhNhu/PortfolioOptimizationUsingMarkowitzMethod/assets/107611691/472b344d-9615-4f4f-b3aa-291e5586a86b)

## 3. Reflection:
- This Mean-Variance Analysis approach is based on the assumption that returns follow a Gaussian distribution in MPT, Then the investors will make decision only based on the consideration of Mean and Variance. However, this assumption is not kept in reality. In reality, the distribution of security prices has fat tail.

- This method would work better if the starting point (the list that investor would choose from to build porfolio) is good.

- optimization algorithm used in this python code is sensitive with wrong, espectially the cubic splines interpolation. Be careful, check the data prior to conduct optimization. 

## 4. Citation
[1] https://www.kenwuyang.com/en/post/portfolio-optimization-with-python/
[2] Fabozzi, Frank & Markowitz, Harry & Gupta, Francis. (2008). Portfolio Selection. 10.1002/9780470404324.hof002001. 
