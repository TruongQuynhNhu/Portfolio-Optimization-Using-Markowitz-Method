# PortfolioOptimizationUsingMarkowitzMethod

## 1. Installation
(1) install all the necessary packages for the project mentioned in file `requirements.txt`

```
pip install -r requirements.txt
```
(2) run file `PortfolioOptimizationUsingMarkowitzMethod.ipynb`

## . Dataset
The dataset includes the historical monthly price of 20 equities on NMS (MCD, WMT, KO, T, BAC, KHC, BA, TSLA, AMZN, AAPL, VZ, PFE, GS, MMM, AXP, CAT, FCAU, UL, COST, XOM) during the period of 5 years from 2016 to 2021. The goal is to use Mean-Variance Analysis Approach proposed by Markowitz in 1952 to find the optimal portfolio, that has the highest Sharpe Ratio.

## 2. Results
Below is the Capital Market Line, which tangents the Efficient Frontier at the optimal portfolio.

**Capital Market Line and Efficient Frontier**

![image](https://github.com/TruongQuynhNhu/PortfolioOptimizationUsingMarkowitzMethod/assets/107611691/e491aa64-a0b5-4268-946b-ea308794cd50)

To achieve the optimal portfolio, the Weights allocation is as below.

**Porfolio Allocation**

![image](https://github.com/TruongQuynhNhu/PortfolioOptimizationUsingMarkowitzMethod/assets/107611691/472b344d-9615-4f4f-b3aa-291e5586a86b)

## 3. Reflection:
- The Mean-Variance Analysis approach in Modern Portfolio Theory (MPT) relies on the assumption that returns adhere to a Gaussian distribution. Consequently, investors base their decisions solely on the Mean and Variance. However, this assumption does not hold in reality. In actuality, the distribution of security prices often exhibits fat tails, indicating more extreme outcomes than predicted by a Gaussian distribution.

- Moreover, the assumption that an optimal portfolio derived from historical data will remain optimal in the future is unrealistic. The dynamic and volatile nature of the securities market renders this assumption impractical. Correlations between assets, which may have been negative in the past, could shift to strongly positive in the future, thus diminishing the benefits of a diversified strategy.

- For this method to be effective, it is crucial to begin with a solid foundation, i.e., a well-curated list of assets from which investors can construct their portfolios.

- Furthermore, the optimization algorithm employed in this Python code is particularly sensitive to inaccuracies, notably in the cubic splines interpolation. It is imperative to exercise caution and meticulously scrutinize the data before initiating the optimization process.

## 4. Citation
[1] https://www.kenwuyang.com/en/post/portfolio-optimization-with-python/
[2] Fabozzi, Frank & Markowitz, Harry & Gupta, Francis. (2008). Portfolio Selection. 10.1002/9780470404324.hof002001. 
