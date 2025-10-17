# 🧾 Python Cheat Sheet for Data Analysis

> © Copyright IBM Corporation 2023.  
> All rights reserved.

A concise and practical reference for performing **data loading**, **wrangling**, **exploration**, **model development**, and **evaluation** using **Python** and **Scikit-Learn**.

---

## 📦 Data Loading

### Read CSV Dataset
```python
# Load without header
df = pd.read_csv(<CSV path>, header=None)

# Load using first row as header
df = pd.read_csv(<CSV path>, header=0)
