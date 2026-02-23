# web-tech-lab-4
# Lab 4 - JavaScript Basics
## README & Repository Documentation
## 📁 Repository Structure
```
Lab-4-JavaScript/
│
├── task1.html          → Product of Two Numbers
├── task2.html          → ATM System with Balance Update
├── task3.html          → Loop Customization
├── task4.html          → Student Result Calculator
├── activity1.html      → ATM System (Lab Activity)
├── activity2.html      → Add Two Numbers
└── README.md           → This File

## 📌 Lab 4 Overview

| No | File | Topic |
|---|---|---|
| Task 1 | task1.html | Product of Two Numbers |
| Task 2 | task2.html | ATM System |
| Task 3 | task3.html | Loop Customization |
| Task 4 | task4.html | Student Result Calculator |
| Activity 1 | activity1.html | ATM System Activity |
| Activity 2 | activity2.html | Add Two Numbers |

## ✅ Task 1 — Product of Two Numbers

### Description
A simple JavaScript program that takes two numbers from the user and displays their product using an alert box.

### Concepts Used
- prompt() — takes input from user
- alert() — displays output
- parseFloat() — converts string to number

### How to Run
1. Open task1.html in browser
2. Click the button
3. Enter two numbers
4. Product appears in alert box

## ✅ Task 2 — ATM System with Balance Update

### Description
A simulated ATM machine that allows users to withdraw and deposit money with balance validation.

### Features
- Starting balance of Rs. 10,000
- Withdraw money from balance
- Deposit money to balance
- Prevents withdrawal if amount exceeds balance
- Shows transaction history
- Reset account to default balance

### Concepts Used
- if / else conditions
- DOM manipulation
- Functions
- Event handling

### How to Run
1. Open task2.html in browser
2. Enter an amount
3. Click Withdraw or Deposit
4. Updated balance is displayed

## ✅ Task 3 — Loop Customization

### Description
Demonstrates three types of loops in JavaScript.

### Features
- Print numbers from 1 to 20
- Print only even numbers from 1 to 20
- Print numbers in reverse order from 10 to 1

### Concepts Used
- for loop
- i++ and i-- (increment and decrement)
- Modulus operator % for even numbers
- DOM manipulation

### Code Logic
```javascript
// Print 1 to 20
for (let i = 1; i <= 20; i++)

// Even Numbers Only
if (i % 2 === 0)

// Reverse 10 to 1
for (let i = 10; i >= 1; i--)

### How to Run
1. Open task3.html in browser
2. Click any button to see output

## ✅ Task 4 — Student Result Calculator

### Description
Calculates total marks, percentage, and grade based on marks entered for 3 subjects.

### Features
- Takes marks for Math, English, Science
- Calculates total out of 300
- Calculates percentage
- Displays grade based on percentage

### Grade Table

| Percentage | Grade | Remark |
|---|---|---|
| 90% – 100% | A | Excellent |
| 70% – 89% | B | Good |
| 50% – 69% | C | Average |
| 40% – 49% | D | Poor |
| Below 40% | F | Fail |

### Concepts Used
- parseFloat() for input
- Arithmetic operators
- if / else if conditions
- DOM manipulation

### How to Run
1. Open task4.html in browser
2. Enter marks for all 3 subjects
3. Click Calculate Result
4. Result card is displayed

---

## ✅ Activity 2 — Add Two Numbers

### Description
Takes two numbers from input fields and displays their sum on the page.

### Problem Fixed
- Replaced HTML encoded &quot; with normal " inside JavaScript

### Concepts Used
- Number() for conversion
- innerHTML to display result
- onclick event

### How to Run
1. Open activity2.html in browser
2. Enter two numbers
3. Click Add
4. Sum is displayed below


## 💡 JavaScript Concepts Covered in Lab 4

| Concept | Used In |
|---|---|
| prompt() and alert() | Task 1 |
| if / else conditions | Task 2, Task 4 |
| for loops | Task 3 |
| Functions | All Tasks |
| DOM manipulation | Task 2, 3, 4 |
| Arithmetic operators | Task 1, 4 |
| Modulus operator % | Task 3 |
| Input validation | Task 2, 4 |

## 🛠️ Tools Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- VS Code (Editor)
- Google Chrome (Browser)

