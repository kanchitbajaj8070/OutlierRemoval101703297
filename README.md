
We use two techniques to detect outliers in our dataset .
1. If z-score >3 then we say that the data point is a outliers
2. Interquantilerange -> if datapoint < lower quantile-1.5*iqr or datapoint > upperquantile+1.5*iqr then it is classified as an outlier
