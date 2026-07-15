# Collatz Conjecture

A simple C++ program that demonstrates the **Collatz Conjecture**, a famous unsolved problem in mathematics. The program accepts a positive integer from the user and generates the Collatz sequence until it reaches 1.

---

## 📖 About the Collatz Conjecture

The Collatz Conjecture, also known as the **3n + 1 Problem**, states that for any positive integer:

- If the number is **even**, divide it by 2.
- If the number is **odd**, multiply it by 3 and add 1.
- Repeat the process until the number becomes **1**.

Although this has been verified for extremely large numbers through computation, no general mathematical proof exists.

### Example

Starting Number: **6**

```
6 → 3 → 10 → 5 → 16 → 8 → 4 → 2 → 1
```

---

## 🚀 Features

- Accepts any positive integer as input.
- Generates the complete Collatz sequence.
- Counts the total number of steps required to reach 1.
- Displays the sequence in a clear format.
- Simple console-based interface.

## 💻 Sample Output

```
   ***COLLATZ CONJECTURE***

        ENTER THE STARTING NUMBER: 5

        SEQUENCE:5-->16-->8-->4-->2-->1

                ***RESULT***
 
        TOTAL STEPS TO REACH 1=5

        HIGHEST PEAK VALUE REACHED=16
```

---

## 📌 Algorithm

1. Read a positive integer `n`.
2. While `n` is not equal to `1`:
   - If `n` is even:
     - `n = n / 2`
   - Else:
     - `n = 3 × n + 1`
3. Print each value in the sequence.
4. Display the total number of steps.

---

## 📚 Mathematical Formula

For a positive integer **n**:

```
           n / 2          if n is even
f(n) =
           3n + 1         if n is odd
```

---

## 🎯 Learning Objectives

This project demonstrates:

- Conditional statements (`if-else`)
- Loops (`while`)
- Integer arithmetic
- User input/output
- Algorithm implementation in C++

---

## 📜 License

This project is available for educational and learning purposes.

---

## 👨‍💻 Author

**JOHN ROHITH**

Electrical and Electronics Engineering  
Government Engineering College, Thrissur
