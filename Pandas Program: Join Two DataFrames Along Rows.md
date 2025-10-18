# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd
student_data1 = {
    'name': ['vijay','ajith', 'dhanush'],
    'score': [85, 90, 88]
}
df1 = pd.DataFrame(student_data1)

student_data2 = {
    'name': ['suriya', 'ragavan', 'bala'],
    'score': [95, 100, 95]
}
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0)
print("Combined Student DataFrame (Row-wise Join):\n")
print(combined_df)
```

## Output
<img width="425" height="289" alt="image" src="https://github.com/user-attachments/assets/5e9003f1-b02e-4f71-9814-eddc35ede717" />

## Result
Thus,the above program executed successfully.
