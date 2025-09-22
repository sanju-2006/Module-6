# Exp.No:26  
## overloading

---

### AIM  
write a python program to perform addition of two complex number using binary '+' operator overloading

class name : complex
---

### ALGORITHM

1. **Begin the program.**
2. **Define the Bird class**:
   - Create a method `intro()` to print "There are many types of birds."
   - Create a method `flight()` to print "Most of the birds can fly but some cannot."
3. **Define the Sparrow class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Sparrows can fly."
4. **Define the Ostrich class**, which inherits from `Bird`:
   - Override the `flight()` method.
   - Call the `intro()` method from the parent class.
   - Print "Ostriches cannot fly."
5. **Create an object `obj_bird`** of the `Bird` class.
6. **Create an object `obj_spr`** of the `Sparrow` class.
7. **Create an object `obj_ost`** of the `Ostrich` class.
8. **Print the general message** "There are many types of birds."
9. **Call the `flight()` method** on each object (`obj_bird`, `obj_spr`, `obj_ost`) to display the respective messages.
10. **Terminate the program.**

---

### PROGRAM

```
class complex:
    def __init__(self, real, imag):
        self.real = real
        self.imag = imag

    def __add__(self, other):
        return complex(self.real + other.real, self.imag + other.imag)

    def __str__(self):
        return f"({self.real}, {self.imag})"


Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
result = Ob1 + Ob2
print(result)
```

### OUTPUT

(3, 5)

### RESULT

<img width="280" height="142" alt="image" src="https://github.com/user-attachments/assets/4b7ed0b6-ad78-44aa-9b4f-e3d704136953" />

