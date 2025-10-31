### Employee Management System

#### Overview
This project is a simple **Employee Management System** implemented in Python.  
It allows you to manage employees, including adding/removing employees, displaying employee details, performing annual reviews, promotions, and salary updates.

The project demonstrates **object-oriented programming (OOP)** concepts such as classes, objects, methods, and encapsulation.

---

#### Features
- Add a new employee with name, age, position, and salary.
- Remove an employee by name.
- Display all employees and their details.
- Perform annual review:
  - Give a raise to employees older than 40.
  - Promote junior developers with a salary increase.
- Find an employee by name.
- Interactive menu to manage employees in a loop.

---
```
#### Project Structure
Employee_Management_System/
├── Management_System.ipynb # Main program with interactive menu
├── README.md # Project documentation
```


#### Classes
##### Employee
- Represents an employee with the following attributes and methods:
###### Attributes
- name, age, position, salary
###### Methods
- give_raise(amount) – Adds the specified amount to the salary.
- promotion(new_position, raise_amount) – Updates position and gives a raise.

##### Manages all employees:
###### Attributes: 
- emp_list (list of Employee objects)
###### Methods
- add_employee(employee) – Add an employee to the system.
- remove_employee(name) – Remove employee by name.
- display_employees() – Show all employees.
- annual_review() – Perform annual review for all employees.
- find(name) – S