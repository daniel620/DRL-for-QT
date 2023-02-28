# DRL for QT
 
## Datasets

### SSE: Shanghai Stock Exchange

#### Close Price
Strong fluctuations can be observed in 2015
![SSE_yearly_trend](data/SSE_yearly_trend.png)

#### Return (log diff)
- Follows a higher peak and fat tail distribution.
(尖峰厚尾)
    - It differs from Gaussian distribution
    - This feature leads to the extension from HMM to HMM-GMD (Gaussian mixture distribution)
    - ![SEE_return_distribution](data/SEE_return_distribution.png)
- Gaussian Mixture Model fit
    - 2 mixture
    - ![SEE_return_distribution_fit](data/SEE_return_distribution_fit.png)

#### MACD
Moving Average Convergence / Divergence
![SSE_MACD](data/SSE_MACD.png)
