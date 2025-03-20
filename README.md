# student-performance-analyzer-C-code

# 🏫 Student Performance Analyzer (SENG 265 - Assignment 3)

## 📌 Overview
This project is a **C program** that processes student performance data from a CSV file and filters the results based on different tasks. It is designed for **Assignment 3 of SENG 265 (Spring 2025)**.

The program reads student data, applies filtering criteria, sorts the records, and writes the results to an output CSV file.

## 🛠 Features
✅ Reads CSV student performance data  
✅ Filters data based on task-specific conditions  
✅ Sorts and limits results based on requirements  
✅ Outputs filtered results in a structured CSV file  

## 📂 File Structure
📦 spf_analyzer
 ┣ 📂 tests/                # Test CSV files
 ┣ 📜 spf_analyzer.c        # Main program file
 ┣ 📜 list.c                # Linked list operations
 ┣ 📜 list.h                # Linked list header file
 ┣ 📜 student.c             # Student struct and functions
 ┣ 📜 student.h             # Student struct definition
 ┣ 📜 emalloc.c             # Safe memory allocation
 ┣ 📜 emalloc.h             # Safe memory allocation header
 ┣ 📜 makefile              # Compilation script
 ┗ 📜 README.md             # Project documentation

## 🎯 **Tasks & Functionality**
The program supports **three tasks**:

### **Task 1 - Extract Record_ID & Exam_Score**
- **Filters:** Extracts only the `Record_ID` and `Exam_Score`
- **Sorting:** Maintains the original order
- **Command Example:**  
  ```bash
  ./spf_analyzer tests/test01.csv 1

### **Task 2 - Extract Top 10 Students Who Studied >40hrs**
- **Filters:** Only includes students who studied more than 40 hours
- **Sorting:** Sorted by Exam_Score (DESC)
- **Command Example:**  
  ```bash
  ./spf_analyzer tests/test02.csv 2

### **Task 3 - Extract Top 10 Students Who Scored 85+**
- **Filters:** Students with Exam_Score >= 85
- **Sorting:** Sorted by Exam_Score (ASC), then Record_ID (ASC)
- **Command Example:**  
  ```bash
  ./spf_analyzer tests/test03.csv 3

