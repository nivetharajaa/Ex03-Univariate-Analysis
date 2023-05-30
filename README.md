# Ex03-Univariate-Analysis

##Aim

##To read the given data and perform the univariate analysis with different types of plots.

##Explanation

Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

##Algorithm

##Step1:

Read the given data.

##Step2:

Get the information about the data.

##Step3:

Remove the null values from the data.

##Step4:

Mention the datatypes from the data.

##Step5:

Count the values from the data.

##Step6:

Do plots like boxplots,countplot,distribution plot,histogram plot.

##Program
##For SuperStore.csv:

Developed by : Nivetha A
Registration Number : 212222230101

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
df['Sales'].value_counts()
sns.boxplot(x="Sales", data=df)
sns.countplot(x="Sales", data=df)
sns.distplot(df["Sales"])
sns.histplot(x="Sales", data=df)

##For diabetes.csv

Developed by : Nivetha A
Registration Number : 212222230101

import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("diabetes.csv.csv")
df
df.head()
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Age'].value_counts()
sns.boxplot(x="Age", data=df)
sns.countplot(x="Age", data=df)
sns.distplot(df["Age"])
sns.histplot(x="Age", data=df)

##OUTPUT

##FOR SuperStore.csv:
##DATA

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/d8b779be-cdc0-4cd9-912e-57330afc6fe4)

##DATA HEAD

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/9a4db02b-2a93-42f8-aaac-842c680fce53)

##DATA INFORMATION

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/094580d5-8989-4f46-8d78-5d397d18cdae)

##DATA DESCRIBE

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/18b89932-c063-4774-b457-8a87f65be789)

##DATA NULL VALUES

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/83d37e79-04f1-480d-a8c1-65fc174948c6)

##DATA DATA TYPES

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/c5689f1a-ef20-4a47-a924-72831f5fd157)

##DATA VALUE COUNT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/a96eaeec-3b02-4243-b5e1-d78e0c0a51b2)

##BOXPLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/ea3bb005-dad0-440c-8103-9cfef5ef2ac1)

##COUNTPLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/d959571d-c600-4d58-b9e8-743c1ee7633c)

##DISTRIBUTION PLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/0af816f1-1ca8-480c-aa8f-8f54eb0dc916)

##HISTOGRAM PLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/f00310d7-aca3-4960-8a33-8708cdaf26ff)

##FOR diabetes.csv:

##DATA

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/8360a2dd-01a1-46a2-937a-fc7abfc78dd6)

##DATA HEAD

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/7a18e972-6bca-4b1d-8207-bfb82bc859db)

##DATA INFORMATION

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/39fcc2c7-3e13-49b8-847a-1dda5d44ea36)

##DATA DESCRIBE

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/80a26f62-b1b5-4e36-8a2e-86aca852a22b)

##DATA NULL VALUES

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/63c59caa-c498-479c-8db2-5bcf8be7f936)

##DATA DATA TYPES

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/db6085ac-a612-4e11-a04f-a2a88a919cca)

##DATA VALUE COUNT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/74dce3da-0852-44a4-b30b-962f59f5476a)

##BOXPLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/a44ffdc9-a95d-4c13-a12a-6e0b06ac07cc)

##COUNTPLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/87c0201c-fcb2-4955-8e9e-922926888ba8)

##DISTRIBUTION PLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/f67ca901-71fd-4c6b-ad08-4a6a8c6ab26e)

##HISTOGRAM PLOT

![image](https://github.com/nivetharajaa/Ex03-Univariate-Analysis/assets/120543388/345aec06-2f69-4707-b334-5c99784ccf4d)

##RESULT

##Thus we have read the given data and performed the univariate analysis with different types of plots.
