# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np
x = np.array([9,7,6,8,10])
y = np.array([5,1,11,4,3])

condition = x >= y

indices = np.where(condition)

print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices[0])

```

## Output
<img width="464" height="197" alt="image" src="https://github.com/user-attachments/assets/3c6f86fc-7767-47b8-b4db-ad0bfbe85e4c" />

## Result
Thus,the above program executed successfully.
