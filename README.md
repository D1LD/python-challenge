# python-challenge
Week2 Python-challenge

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRyk4Nz-eabxVLVrrvEh0yt4wHqHK7ciQBIH7yY4dwLrg&s)


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
