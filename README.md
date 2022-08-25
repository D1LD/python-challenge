# python-challenge
Week2 Python-challenge

![image](https://drive.google.com/file/d/1o_oiFUaQ0P3T_uDdTZIw73x_cr8ruTqQ/view?usp=sharing)


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
