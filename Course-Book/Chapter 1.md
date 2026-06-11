# Chapter 1: Introduction - Programming for Everybody 🚀

This section contains my notes, structural diagrams, and code snippets based on Chapter 1 of the "Python for Everybody" curriculum. It covers the core architecture of computers, how code interacts with hardware, and the fundamentals of writing Python programs.

---

## 🏗️ 1. Computer Hardware Architecture

To write efficient code, we must understand how the computer's internal components interact. A programmer acts as a coordinator between these elements:

*   **Central Processing Unit (CPU):** The brain of the computer. It executes instructions at incredible speeds, constantly asking, *"What next?"* Programs provide the answers to that question.
*   **Main Memory (RAM):** Ultra-fast, temporary storage used by the CPU to hold data needed right now. Its contents are lost when the computer powers off.
*   **Secondary Memory (Hard Drive / Flash):** Slower than RAM, but permanent. It safely stores our files and Python scripts (`.py`) even without power.
*   **Input/Output Devices (I/O):** The keyboard, mouse, and screen that allow us to interact with the software system.

---

## 🗣️ 2. The Language of Python & Reserved Words

Python is a high-level language designed to be readable. It operates with a very strict and limited vocabulary called **Reserved Words** (or Keywords). 

*   These words have a fixed, unchangeable meaning to the Python interpreter (e.g., `if`, `else`, `for`, `while`, `def`, `import`, `print`).
*   Any word we use outside of this reserved vocabulary must be explicitly defined by us as variables or functions; otherwise, the interpreter throws a `SyntaxError`.

---

## 💻 3. Talking to the Interpreter

When we open the Python interactive console, the prompt changes to `>>>`, signaling that the interpreter is waiting for instructions. 

*   **The Dialogue:** If we communicate using standard human grammar, the system fails to understand. We must use precise syntax.
*   **The Execution:** Writing our first command tells the CPU exactly what to process:

```python
# My first Python script in this course
print("Hello, World!")
