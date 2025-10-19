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
```
class Beans:
    def type(self):
        print("Vegetable")
    def color(self):
        print("Green")
class Mango:
    def type(self):
        print("Fruit")
    def color(self):
        print("Yellow")

#creating objects
obj_beans = Beans() 
obj_mango = Mango() 
for i in (obj_beans,obj_mango):
    i.type()
    i.color()
```

## Output
<img width="550" height="439" alt="image" src="https://github.com/user-attachments/assets/aa28c587-61fe-46f5-8086-ebe0e7414401" />


## Result
Thus the program is executed successfully.
