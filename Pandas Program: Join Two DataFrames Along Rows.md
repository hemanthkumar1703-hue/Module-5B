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
~~~
import pandas as pd

a=eval(input())
b=eval(input())
df1=pd.DataFrame(a)
df2=pd.DataFrame(b)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
print()
con=pd.concat([df1,df2])
print("Join the said two dataframes along rows:")

print(con)
~~~

Add code here

## Output
<img width="1058" height="480" alt="image" src="https://github.com/user-attachments/assets/1d323816-5df9-4cc5-af12-b338750aad0e" />

## Result
Thus the program to write a Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame is executed successfully
