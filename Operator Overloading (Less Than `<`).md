# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```class Marks:
    def __init__(self, value):
        self.value = value


    def __gt__(self, other):
        return self.value > other.value


obj1 = Marks(20)
obj2 = Marks(10)

print(obj1 > obj2)
```
## Output
<img width="1206" height="274" alt="image" src="https://github.com/user-attachments/assets/52aaaf6e-df17-4aab-9a16-0ba8e46cbea3" />

## Result
Thus the program is executed successfully.
