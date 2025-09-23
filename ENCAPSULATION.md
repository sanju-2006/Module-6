# Exp.No:29  
## Encapsulation

---

### AIM  
Create a class Employee with public method show to display the details of the employee.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```

class Employee:
    # constructor
    def __init__(self, name, salary):
        # public data members
        self.name = name
        self.salary = salary

    # public instance methods
    def show(self):
        print(f"Name:  {self.name} Salary: {self.salary}")
# creating object of a class
emp = Employee('Jessa', 10000)

# accessing public data members
print("Name: ", emp.name, 'Salary:', emp.salary)
emp.show()

```

### OUTPUT

<img width="699" height="181" alt="image" src="https://github.com/user-attachments/assets/15d6ddc3-23f9-4cca-91c8-8a63af04bd48" />



### RESULT

Create a class Employee with public method show to display the details of the employee is successfully verified



