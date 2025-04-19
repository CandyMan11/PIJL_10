# PIJL_10


# Java Multi-Threading Demonstration

## 👨‍💻 Student Information
**Name:** Saksham Sharma  
**PRN:** 23070126113  
**Batch:** AIML B2  

---

## 📌 Project Description

This project demonstrates the use of **multithreading in Java**. The main goal is to show how different threads can run concurrently and perform different tasks independently.

Each thread performs a unique operation:
- **NumberThread** prints numbers from 1 to 5.
- **CharacterThread** prints characters from A to E.
- **SquareThread** prints the squares of numbers from 1 to 5.

---

## 🗃️ Project Structure

```
Assignment_10/
├── Main.java             // Main class to start all threads
├── NumberThread.java     // Thread to print numbers
├── CharacterThread.java  // Thread to print characters
└── SquareThread.java     // Thread to print squares
```

Each file contains a single class, and the code follows Java best practices. All operations are modularized into individual methods for clarity and reusability.

---

## ⚙️ How to Compile and Run

### 💻 Step 1: Open your terminal or command prompt  
Navigate to the directory containing the files.

```bash
cd path/to/Assignment_10
```

### 🧪 Step 2: Compile the Java files

```bash
javac Main.java NumberThread.java CharacterThread.java SquareThread.java
```

### 🚀 Step 3: Run the program

Make sure to run with the package if specified:

```bash
java Assignment_10.Main
```

If package declaration is removed or not used, you can simply run:

```bash
java Main
```

---

## 📒 Features

- Demonstrates basic **Java thread creation and execution**.
- Each class handles a **single responsibility**.
- Uses **`Thread` class inheritance**.
- **Clean modular structure** with one method per task.
- Uses proper **exception handling** and coding standards.

---

## 📘 Sample Output

```
Main Thread Started
NumberThread Started
CharacterThread Started
SquareThread Started
NumberThread: 1
CharacterThread: A
SquareThread: 1^2 = 1
...
Main Thread Ended
```

(Note: Actual output may vary due to thread execution order)

---

## 🧠 Concepts Covered

- Java Multithreading (`Thread` class)
- Concurrent Execution
- Thread Sleeping and Delays
- Try-Catch for InterruptedException
- Modular Programming in Java
- Multi-file Project Compilation

---

## ✅ Author

Made with ❤️ by **Saksham Sharma**  
**Batch:** AIML B2  
**PRN:** 23070126113  
