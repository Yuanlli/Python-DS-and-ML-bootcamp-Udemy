# SF-Employee-Salary-Python-Data-Analysis
## 👩‍💻 Data exploration using Python

Pandas exercise from the Python for Data Science with Machine Learning Bootcamp from Udemy.

This data contains the names, job title, and compensation for San Francisco city employees on an annual basis from 2011 to 2014. Dataset is from Kaggle https://www.kaggle.com/datasets/kaggle/sf-salaries/data

#### 1) Import pandas package
```python
import pandas as pd
```

#### 2) Read the Salaries.csv as 'sal'
```python
sal = df.read_csv('Salaries.csv')
print = sal
```
![1](https://github.com/Yuanlli/SF-Employee-Salary-Python-Data-Analysis/assets/35889216/720c6b4e-dac8-4e00-a349-d7f4e6e5ea32)


#### 3) Find the number of entries
```python
sal.info()
```
![Capture2](https://github.com/Yuanlli/SF-Employee-Salary-Python-Data-Analysis/assets/35889216/5ac1010f-86d6-439c-98f0-4673cd0a9b16)

#### 4) Find average base pay
```python
sal['BasePay'].mean()
```
-- The average BasePay is 66325.4488404877


