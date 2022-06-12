# ⚙️Model Development⚙️
Mathematical Equation used to predict value given one or more values.

#### Linear Regression:
Relation between predictor x and target y
$$y=b_0 + b_1x  \space \space\space \space\space[b_0: the \space intercept; \space b_1=slope]$$
#### Multiple Linear Regression :
$$ \hat{Y} = b_0+b_1x_1+b_2x_2+b_3x_3.... \space\space [b_1= coefficient \space or \space parameter \space of \space x_1]$$
#### MLR: Estimated Linear Model:
1. Find the Intercept (b <sub>0</sub>  ) 
2. Find the coefficients (b <sub>1</sub> b <sub>2</sub> ,b <sub>3</sub> ,b <sub>4</sub> )

## Model Evaluation using Visualization:👀
1. Regression Plot:\
&emsp; It gives us a good estimate of:\
&emsp;&emsp; a. The relationship between two variables.\
&emsp;&emsp; b. The strength of the correlation.\
&emsp;&emsp; c. The direction of the relationship (positive or negative).\
&emsp; Regression plot shows us combination of:\
&emsp;&emsp; - The scatter plot: each point representing a different y.\
&emsp;&emsp; - The fitted linear regression line ($\hat{Y}$)\
![image](https://user-images.githubusercontent.com/69965983/173245514-264503cb-190e-44fb-a65b-82e6e277a81f.png)

2. Distribution Plot:\
&emsp; Compare the distribution plots:\
&emsp;&emsp; - The fitted values that result from the model.\
&emsp;&emsp; - The actual values.\
![image](https://user-images.githubusercontent.com/69965983/173245619-163731ea-20d2-4f07-b089-4e2f7dfcd169.png)\
&emsp; Distribution Plot for MLR:
```python 
import seaborn as sns
axl = sns.distplot(dataframename['value'], hist=False, color="r", label="Actual Value")
sns.distplot(Yhat, hist=False, color"b", label="Fitted Values", as=as1)
```

3. Residual Plot:
```python
import seaborn as sns
sns.residplot(dataframename['value1'], dataframename['value2'])
```
![image](https://user-images.githubusercontent.com/69965983/173245819-01821153-4924-454d-90ee-ff2fee871066.png)


