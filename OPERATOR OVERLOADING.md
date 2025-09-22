# Exp.No:27  
## binary '+' operator overloading

---

### AIM  
write a python program to perform subtraction of two complex number using binary '+' operator overloading

class name : complex


Ob1 = complex(1, 2)
Ob2 = complex(2, 3)

---

### ALGORITHM

1. **Start the Program.**
2. **Define the Complex class**:
   - Define the constructor `__init__()` to accept two parameters: `real` and `imag` (representing the real and imaginary parts of the complex number).
   - Assign these values to `self.real` and `self.imag` respectively.
3. **Define the `__truediv__()` method** to perform the division of two complex numbers:
   - Calculate the real part of the result as the division of `self.real` by `other.real`.
   - Calculate the imaginary part of the result as the division of `self.imag` by `other.imag`.
   - Return a new Complex object with the calculated real and imaginary parts.
4. **Define the `__repr__()` method** to represent the complex number as a string.
   - Return a string formatted to display the real and imaginary parts with one decimal place using `f"{self.real:.1f}, {self.imag:.1f}"`.
5. **Create two objects of the Complex class**:
   - `Ob1 = Complex(10, 21)` represents the complex number `10 + 21i`.
   - `Ob2 = Complex(2, 3)` represents the complex number `2 + 3i`.
6. **Perform the division operation**: Use the `/` operator to divide `Ob1` by `Ob2`. This will call the `__truediv__()` method.
7. **Print the result**: Print the result of the division, which will be formatted by the `__repr__()` method.
8. **End the Program.**

---

### PROGRAM

```
class complex:
    def __init__(self, a, b):
        self.a = a
        self.b = b
    
    def __sub__(m1,m2):
        x=m1.a-m2.a
        y=m1.b-m2.b
        return x,y
Ob1 = complex (1, 2)
Ob2 = complex(2, 3)
Ob3 = Ob1 - Ob2
print(Ob3)
```

### OUTPUT

(-1, -1)

### RESULT


<img width="349" height="142" alt="image" src="https://github.com/user-attachments/assets/22cbce50-35a8-4a23-9edb-e3c6bcf5a568" />

