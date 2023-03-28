# Ex03-Univariate-Analysis

# Aim

To read the given data and perform the univariate analysis with different types of plots.

# Explanation

Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm

# Step1

Read the given data.

# Step2

Get the information about the data.

# Step3

Remove the null values from the data.

# Step4

Mention the datatypes from the data.

# Step5

Count the values from the data.

# Step6

Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program

```
Developed by : KAMALI E
Registration Number : 212222110015

import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
df
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x="Postal Code", data=df)
sns.countplot(x="Postal Code", data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x="Postal Code", data=df)
```

# OUTPUT

# DATA
![1](https://user-images.githubusercontent.com/120567837/228320149-5e55eba5-9002-4473-97c7-ad68d6f8b9bf.png)


# DATA HEAD

![2](https://user-images.githubusercontent.com/120567837/228320193-71f6506f-ec9e-494c-86ed-19847f6b9d2d.png)


# DATA INFORMATION

![3](https://user-images.githubusercontent.com/120567837/228320230-b8ed3403-6651-45b2-b195-916cf2cc7c50.png)


# DATA DESCRIBE 

![4](https://user-images.githubusercontent.com/120567837/228320264-cc8e1a82-72bf-4bd8-8e51-60492af253b2.png)


# DATA NULL VALUES

![5](https://user-images.githubusercontent.com/120567837/228320284-633287da-6a90-41be-9b93-c93b1768b882.png)


# DATA DATA TYPES

![6](https://user-images.githubusercontent.com/120567837/228320330-09145f51-61e1-4622-a23c-0e663d46d43f.png)


# DATA VALUE COUNT

![7](https://user-images.githubusercontent.com/120567837/228320356-26ebe542-2a28-4a6c-a1ce-4eae86276ab0.png)


# BOXPLOT

![8](https://user-images.githubusercontent.com/120567837/228320407-a0b84471-b8f6-4edf-94c1-bef279f5ca4d.png)


# COUNTPLOT

![9](https://user-images.githubusercontent.com/120567837/228320447-a52c08d9-420f-40fe-9538-587b8091016b.png)


# DISTRIBUTION PLOT

![10](https://user-images.githubusercontent.com/120567837/228320477-70071f31-c8d2-4916-8199-6a2ace30d14d.png)


# HISTOGRAM PLOT

![11](https://user-images.githubusercontent.com/120567837/228320510-00b0aeee-3314-4b09-958d-db0da33a8be7.png)


# RESULT

Thus we have read the given data and performed the univariate analysis with different types of plots.
