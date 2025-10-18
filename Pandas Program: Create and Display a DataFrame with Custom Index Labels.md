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
```
import pandas as pd
exam_data = {
    'name': ['vijay', 'Joseph', 'priya', 'Ravi', 'Nila', 'Arjun', 'ajith', 'suriya'],
    'score': [100, 95, 98, 25, 29, 100, 80,70],
    'attempts': [1, 3, 2, 3, 2, 3, 1, 1],
    'qualify': ['yes', 'yes', 'yes', 'no', 'no', 'yes', 'yes', 'yes']
}

labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']

df = pd.DataFrame(exam_data, index=labels)
print("Exam Results DataFrame:\n")
print(df)
```

## Output
<img width="352" height="312" alt="image" src="https://github.com/user-attachments/assets/c44d9e11-59a5-4953-9958-31534194c151" />

## Result
Thus,the above program executed succesfully.
