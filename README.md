# 🐍 Python Study Guide: Types and Comparisons

This repository covers **Python data types** and how to compare **numbers and strings** using different operators. It also introduces **string formatting**.

---

## 📌 Topics Covered

1. **Comparing Numbers**
2. **Types and Comparisons**
3. **Comparing Strings (Equality Operator)**
4. **String Formatting**

---

## 📝 1. Comparing Numbers

Python provides **comparison operators** for numbers:

| Operator | Description | Example |
|----------|------------|---------|
| `==` | Equal to | `5 == 5` → `True` |
| `!=` | Not equal to | `5 != 3` → `True` |
| `>` | Greater than | `10 > 7` → `True` |
| `<` | Less than | `3 < 8` → `True` |
| `>=` | Greater than or equal | `10 >= 10` → `True` |
| `<=` | Less than or equal | `2 <= 5` → `True` |

Example:

```python
x = 10
y = 5

if x > y:
    print("x is greater than y")
