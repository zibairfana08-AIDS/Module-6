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
```
class A:
    def __init__(self, a):
        self.a = a

   
    def __lt__(self, other):
        if self.a < other.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"


ob1 = A(10)
ob2 = A(20)


print(ob1 < ob2)
```
## Output
<img width="915" height="332" alt="502953854-21fdf6a8-006b-40e7-b499-2d2e7a4d152f" src="https://github.com/user-attachments/assets/9a9bed8a-51a3-47bd-a978-5ce224eb823b" />

## Result
a Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class is executed successfully.
