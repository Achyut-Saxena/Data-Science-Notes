# What is Polynomial Regression?💻
Special case of general linear regression.
- Quadratic:
$$\hat{Y} = b_0 +b_1x_1+b_2(x_1)^2$$
- Cubic:
$$\hat{Y} = b_0 +b_1x_1+b_2(x_1)^2+b_3(x_3)^3$$
-  Higher Order:
$$\hat{Y} = b_0 +b_1x_1+b_2(x_1)^2+b_3(x_3)^3+...$$
![image](https://user-images.githubusercontent.com/69965983/173277153-a3a9e1da-5128-4042-99dd-4ef2a5eba2cb.png)
![image](https://user-images.githubusercontent.com/69965983/173277172-4030ca2c-1e44-4bfd-ad4d-548ba86b0259.png)

## Pipelining:
![image](https://user-images.githubusercontent.com/69965983/173291571-88197695-c41b-4159-a9ae-6e3dc300dcbb.png)

![image](https://user-images.githubusercontent.com/69965983/173291635-035d4bef-1297-4cc3-b362-1b047574ee97.png)


## Measures for In-Sample Evaluation:
1. Mean Squared Error (MSE):\
&emsp; Steps:\
&emsp;&emsp; 1. Square Difference between Y (actual) and $\hat{Y}$ (predicted)\
&emsp;&emsp; 2. Take mean of all the errors by adding all the error squares and dividing by total number of samples.\
```python
from sklearn.metrics import mean_squared_error
mean_squared_error(dataframename['value'], Y_predict_simple_fit)
```
2. $R^2$ (R-squared):
- The coefficient of Determination or $R^2$
- Is a measure to determine how close the data is to the fitted regression line.
- $R^2$: the percentage of variation of the target variable (Y) that is explained by the linear model.

$$R^2=(1-\frac{MSE\space of\space regression\space line}{MSE\space of \space the \space average\space of\space data})$$
