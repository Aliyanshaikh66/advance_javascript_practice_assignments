# advance_javascript_practice_assignments


# JavaScript Advanced (ES6+) – 15 Practical Assignments

Har assignment ka purpose ye hai ke students ko **real-world use**, **practice**, aur **benefits** samajh aa jayein.

---

# Assignment 1: Student Profile Card Generator

### Topics

* Template Literals
* Default Parameters
* Enhanced Object Literals

### Task

Ek function banao jo student ka profile card generate kare.

```js
createProfile("Ali", 20, "Web Development");
```

Output:

```
Name: Ali
Age: 20
Course: Web Development
```

### Real Use

Social media profiles, LMS systems.

### Benefits

* Dynamic strings banana
* Default values dena
* Object ko easily create karna

---

# Assignment 2: E-Commerce Cart

### Topics

* Spread Operator
* Destructuring

### Task

2 arrays ko merge karo:

```js
cart1 = ["Shoes", "Bag"];
cart2 = ["Watch", "Laptop"];
```

Aur first item alag variable me destructure karo.

### Real Use

Shopping websites.

### Benefits

* Arrays merge karna
* Data extract karna

---

# Assignment 3: Theme Switcher

### Topics

* Ternary Operator

### Task

```js
isDarkMode = true;
```

Output:

```
Dark Theme Enabled
```

warna:

```
Light Theme Enabled
```

### Real Use

Dark/Light mode websites.

### Benefits

Code short aur readable hota hai.

---

# Assignment 4: Employee Salary Calculator

### Topics

* Arrow Functions

### Task

Salary me 10% bonus add karna.

```js
50000 => 55000
```

### Real Use

Payroll systems.

### Benefits

Short syntax aur callbacks me zyada use hota hai.

---

# Assignment 5: Bank Account System

### Topics

* Closure

### Task

Balance private rahe aur sirf deposit aur withdraw function se access ho.

```js
deposit(500)
withdraw(200)
```

### Real Use

ATM aur banking systems.

### Benefits

Data hiding aur security.

---

# Assignment 6: User Login System

### Topics

* Variable Scoping

### Task

Global variable:

```js
let appName = "TechNetCloud";
```

Local variable:

```js
let username = "Ali";
```

Check karo local variable bahar accessible na ho.

### Real Use

Authentication systems.

### Benefits

Memory aur security improve hoti hai.

---

# Assignment 7: Product Details Viewer

### Topics

* Optional Chaining

### Task

Kuch products me reviews nahi hain.

```js
product.review?.rating
```

Error nahi aana chahiye.

### Real Use

E-commerce websites.

### Benefits

Application crash nahi hoti.

---

# Assignment 8: Weather App

### Topics

* Destructuring
* Template Literals

### Task

Object:

```js
{
 city:"Karachi",
 temp:35,
 humidity:80
}
```

Output:

```
Karachi Temperature is 35°C and humidity is 80%
```

### Real Use

Weather APIs.

### Benefits

API data easily access karna.

---

# Assignment 9: Quiz Application

### Topics

* Arrow Functions
* Ternary Operator

### Task

Marks 50 se zyada hon to:

```
Pass
```

warna:

```
Fail
```

### Real Use

Online Quiz System.

### Benefits

Conditional logic aur functions ki practice.

---

# Assignment 10: Team Management System

### Topics

* Spread Operator

### Task

Developers aur Designers arrays ko combine karo.

### Real Use

HR systems.

### Benefits

Data merge karna seekhenge.

---

# Assignment 11: Library Management System

### Topics

* Enhanced Object Literals
* Default Parameters

### Task

Book object banao:

```js
title
author
available = true
```

### Real Use

Library software.

### Benefits

Object creation easy hoti hai.

---

# Assignment 12: Chat Application

### Topics

* Modules

### Task

Files banao:

### math.js

```js
export function add(a,b){
 return a+b;
}
```

### app.js

```js
import {add} from "./math.js";
```

### Real Use

React, Node.js, Next.js projects.

### Benefits

Large projects ko manage karna.

---

# Assignment 13: Food Delivery App

### Topics

* Optional Chaining
* Destructuring

### Task

Restaurant object me menu missing ho sakta hai.

```js
restaurant.menu?.pizza
```

### Real Use

Foodpanda, Uber Eats.

### Benefits

API data safely access karna.

---

# Assignment 14: Counter App

### Topics

* Closure
* Arrow Functions

### Task

Counter private ho:

```js
increment()
decrement()
```

Outside se direct access na ho.

### Real Use

Like button, notification count.

### Benefits

State management samajh aayegi.

---

# Assignment 15: Mini Student Management System ⭐

## (Capstone Assignment)

### Topics Covered

✅ Variable Scoping
✅ Closure
✅ Template Literals
✅ Destructuring
✅ Default Parameters
✅ Spread Operator
✅ Arrow Functions
✅ Enhanced Object Literals
✅ Modules
✅ Ternary Operator
✅ Optional Chaining

### Features

1. Add Student
2. Display Students
3. Search Student
4. Merge Two Classes
5. Show Marks Status

```js
marks >= 50 ? "Pass" : "Fail"
```

6. Student Profile

```js
`${name} is enrolled in ${course}`
```

7. Missing Data Handle

```js
student.address?.city
```

8. Separate Modules

```
student.js
display.js
app.js
```

## Real Use

* LMS
* School Management System
* University Portals

## Benefits

Students ko samajh aayega ke ye tamam ES6 concepts real projects me kahan use hote hain aur future me React, Node.js aur MERN Stack seekhne me bahut madad milegi.

---

### Best Practice

Har assignment ke sath students se ye 4 cheezein zarur submit karwaen:

1. **Code**
2. **Output Screenshot**
3. **1 paragraph explanation:** "Is topic ka real-world use kya hai?"
4. **GitHub Repository Link**

<!-- Is tarah unki coding ke sath-sath thinking aur practical understanding bhi strong hogi. -->
