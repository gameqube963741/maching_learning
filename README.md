# maching_learning

### 具正則化回歸 Lasso、Ridge regression 回歸模型建構
### information gain 資訊獲利
### DecisionTree 決策樹
### KNN 模型建模
### 購物籃分析

### 觀察資料
df.head()
df.describe()
df.shape()
df.value_counts()
unique()
ununique()

# Exploring Data Analysis
## hist
## boxplot
## ECDF (Empirical Cumulative Distribution Function)

### Histgram
#### Import necessary modules
import pandas as pd
import matplotlib.pyplot as plt
##### Create the hist
df.hist(column='initial_cost')
##### Display the plot
plt.show()

### Boxplot
#### Import necessary modules
import pandas as pd
import matplotlib.pyplot as plt
#### Create the boxplot
df.boxplot(column='initial_cost', by='Borough', rot=90)
#### Display the plot
plt.show()