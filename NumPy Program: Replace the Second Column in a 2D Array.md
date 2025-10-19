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
```
import numpy as np
a=np.array(eval(input()))
new=np.array(eval(input()))
b=np.delete(a,1,axis=1)
c=np.insert(b,1,new,axis=1)
print("Printing Original array")
print(a)
print("Array after deleting column 2 on axis 1")
print(b)
print("Array after inserting column 2 on axis 1")
print(c)
```

## Output
<img width="920" height="452" alt="image" src="https://github.com/user-attachments/assets/3ad33cd0-d353-4060-ad53-dd66a3055916" />

## Result
The program is excecuted
