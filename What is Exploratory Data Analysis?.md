### 🔍What is Exploratory Data Analysis?🔎
The preliminary step in data analysis is to:
- Summarize main characteristics of data set
- Gain better understanding of data set
- Uncover relationships between variables
- Extract important variables

#### Descriptive Statistics: 📓
- Using Describe Function 
- Value_Counts() Function 
- Box Plots 
- Scatter Plots 

#### Grouping Data: 🧑‍🤝‍🧑
- groupby() method 

#### Correlation: ⛓️
- Measures to what extent different variables are interdependent
Eg:
Lung Cancer -> Smoking
Rain -> Umbrella

#### Correlation Statistics: 📊
- ##### Pearson Correlation :
&emsp;It is to measure strength of the correlation between two features.\
  &emsp;a. Correlation Coefficient:\
    &emsp;&emsp;- Close to +1: Large Positive Relationship\
    &emsp;&emsp;- Close to -1: Large Negative Relationship\
    &emsp;&emsp;- Close to 0: No Relationship\
  &emsp;b. P-Value:\
    &emsp;&emsp;- <0.001: Strong Certaininty in the result\
    &emsp;&emsp;- <0.05: Moderate Certaininty in the result\
    &emsp;&emsp;- <0.1: Weak Certaininty in the result\
    &emsp;&emsp;- >0/1: No Certaininty in the result\

  &emsp;Strong Correlation:
    - Correlation Coefficient close to 1 or -1
    - P-value less than 0.001

- ##### Chi-square Test for Association:
&emsp;- The $\chi^2$ tests a null hypothesis that the variables are independent.\
&emsp;- The &\chi^2& does not tell the type of relation that exists between both the variables; but only that relationship exists.

$$\chi^2 = \Sigma_{i=1}^n \frac{(O_i-E_i)^i}{E_i}$$

_P-Value <0.05, we reject the nill hypothesis that the two variables are independent and conclude that there is evidence of association between them._
