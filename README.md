# The predict API
The predict API enables to project a data set (financial data, crypto data, sensor data…) over a projection horizon, using an innovative stochastic approach.
# Quick start
```
from predict import quantiles
api_key = "your_rapidapi_key"
data = [518.4, 559.9, 553.19, 524.57, 567.65, 531.75, 576.45, 514.42]
horizon = 5
cls = [0.2, 0.5, 0.8, 1]
quantiles = quantiles(api_key, data, horizon, cls)
print(quantiles)
```
