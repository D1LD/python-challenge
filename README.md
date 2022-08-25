### python-challenge
##Week2 Python-challenge

#Due to issue with Anaconda and Git,run homework on Colab


from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
path = "/content/drive/MyDrive/Colab Notebooks/home22.csv"
df = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/home22.csv") 


df.head()
rows = len(df.axes[0])
print(df)
print("ToTal Months: ", rows)

import numpy as np
import pandas as pd




Total = df['Profit/Losses'].sum()
print ("Total Profit is " , Total),
a=df['Profit/Losses'].max()
b=df['Profit/Losses'].min()

print("Greatest increase is " , a)
print("Greatest decrease is " , b),

c =df['Profit/Losses'].mean()
print("Average of the changes is " , c)

Profit/Losses       Date

0          867884  1/01/2010

1          984655  1/02/2010

2          322013  1/03/2010

3          -69417  1/04/2010

4          310503  1/05/2010
..            ...        ...
81         102685  1/10/2016

82         795914  1/11/2016

83          60988  1/12/2016

84         138230  1/01/2017

85         671099  1/02/2017



[86 rows x 2 columns]


ToTal Months:  86


Total Profit is  38382578


Greatest increase is  1170593

Greatest decrease is  -1196225

Average of the changes is  446309.0465116279
