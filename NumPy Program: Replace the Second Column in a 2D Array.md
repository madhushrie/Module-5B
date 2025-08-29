# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

import numpy as np

m=np.array(eval(input()))

n=np.array(eval(input()))

print("Printing Original array")

print(m)

new=np.delete(m,1,axis=1)

print("Array after deleting column 2 on axis 1")

print(new)

after=np.insert(new,1,n[:,0],axis=1)

print("Array after inserting column 2 on axis 1")

print(after)

## Output
<img width="1206" height="818" alt="image" src="https://github.com/user-attachments/assets/ac77e95b-01ae-48d7-97d5-c58d4f2139cb" />

## Result
Thus the program is executed successfully.
