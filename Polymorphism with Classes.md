# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
It is similar to the above question.
```
class Turtle:
    def type(self):
        print("turtle")


class Frog:
    def type(self):
        print("frog")



turtle = Turtle()
frog = Frog()


animals = (turtle, frog)


for animal in animals:
    animal.type()
```
## Output
<img width="1279" height="281" alt="image" src="https://github.com/user-attachments/assets/4c5ada10-2aa1-4654-972b-6b2348c105e6" />

## Result
Thus the program is executed successfully.
