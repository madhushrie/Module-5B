# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program

import pandas as pd

import numpy as np

exam={'name':['Aman','Kamal','Amjad','Rohan','Amit','Sumit','Matthew','Kartik','Kavita','Pooja'],'perc':[79.5,29.0,90.5,np.nan,32,65,56,np.nan,29,89],'qualify':
['yes','no','yes','no','no','yes','yes','no','no','yes']}

lab=['A','B','C','D','E','F','G','H','I','J']

df=pd.DataFrame(exam,index=lab)

print("Original data frame:")

print(df)

ch=input().strip()

per=float(input())

print("Change the percentage in row "+ch+" to",per)

df.loc[ch,'perc']=per

print(df)


## Output
<img width="1015" height="683" alt="image" src="https://github.com/user-attachments/assets/05a69dc7-bd9b-43c0-b9f2-417829b08cb4" />

## Result
Thus the program is executed successfully.
