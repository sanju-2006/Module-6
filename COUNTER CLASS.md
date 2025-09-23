# Exp.No:30  
## Polymorphism

---

### AIM  
Python program to create two classes Ferrari and BMW. They have the same instance method names fuel_type() and max_speed(). However, we have not linked both the classes nor have we used inheritance. Pack two different objects into a tuple and iterate through it using a car variable. 



---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
class Ferrari:
    def fuel_type(self):
        print("Petrol")

    def max_speed(self):
        print("Max speed 350")

class BMW:
    def fuel_type(self):
        print("Diesel")

    def max_speed(self):
        print("Max speed is 240")

ferrari = Ferrari()
bmw = BMW()

# iterate objects of same type
for car in (ferrari, bmw):
    car.fuel_type()
    car.max_speed()
```

### OUTPUT

<img width="458" height="213" alt="image" src="https://github.com/user-attachments/assets/24afcbaf-7c22-43ed-9a35-839cff5f689a" />


### RESULT

Python program to create two classes Ferrari and BMW is successfully verified
