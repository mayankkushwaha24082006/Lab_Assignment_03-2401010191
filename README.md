# 📘 Student Management System – Assignment 3
A Java console-based application that demonstrates exception handling, multithreading, wrapper classes, and input validation. This implementation follows the exact requirements from the assignment document.

## 🚀 Features
### ✔ Input Validation
☞Checks for empty name, email, course
☞Ensures marks are between 0 and 100
☞Handles incorrect numeric input using try-catch

### ✔ Exception Handling
Uses:

☞try-catch-finally
☞NumberFormatException
☞Custom exception: StudentNotFoundException

### ✔ Multithreading
Simulates a loading animation using a separate thread:
Loading.....
(Implements Runnable → Loader class)

### ✔ Wrapper Classes
Uses:

☞Integer for roll number
☞Double for marks
☞Demonstrates autoboxing and data conversion

### ✔ Student Record Management
☞Add a student
☞Store using HashMap
☞Display student details
☞Validate input
☞Auto-calculate grade

## 🧰 Technologies & Concepts Used
☞Java OOP (classes, objects, abstraction)
☞Custom exception
☞Multithreading (Thread, Runnable)
☞Wrapper classes (Integer, Double)
☞Exception handling
☞HashMap
☞Autoboxing & Unboxing

## 📂 File Structure (All in One File)
StudentManagementSystem.java

This single file contains:

☞Custom exception class
☞Loader thread
☞Student class
☞RecordActions interface
☞StudentManager class
☞Main class with menu + logic

## ▶️ How to Run
1.Create a file named:

StudentManagementSystem.java
2.Copy the full code into the file.

3.Compile:

javac StudentManagementSystem.java
4.Run:
java StudentManagementSystem

## 🎯 Learning Outcomes
After completing this assignment, you will understand:

☞How to handle runtime exceptions
☞How try-catch-finally works
☞How to create and use custom exceptions
☞How to use multithreading for UI responsiveness
☞How wrapper classes help in data conversion
☞How to build a robust input system in Java



