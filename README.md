

A comprehensive **Compiler Design Laboratory Project** built using **Python** and **Streamlit**. This project provides practical implementations of important compiler concepts such as lexical analysis, parsing techniques, grammar processing, automata visualization, and intermediate code generation through an interactive IDE.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Modules Included](#modules-included)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Compiler Lab Experiments](#compiler-lab-experiments)
- [Technologies Used](#technologies-used)
- [Learning Outcomes](#learning-outcomes)
- [Future Enhancements](#future-enhancements)
- [Author](#author)
- [License](#license)

---

## 🎯 Overview

Compiler Design is a core subject in Computer Science that focuses on translating high-level programming languages into machine-level instructions.

This project is developed as an educational tool that combines multiple compiler experiments into one modern platform. Instead of running each program separately, students can explore different compiler concepts through a single Streamlit-based interface.

The project demonstrates:

- Lexical Analysis  
- Grammar Processing  
- Parsing Techniques  
- Automata Theory  
- Intermediate Code Concepts  
- Visual Compiler Structures  

---

## ✨ Features

### 💻 Interactive Web Interface
Built using Streamlit with sidebar navigation.

### 🔍 Lexical Analyzer
Breaks source code into tokens such as identifiers, numbers, operators, and keywords.

### 📘 FIRST and FOLLOW
Computes grammar sets used in parser construction.

### 🔄 Infix to Postfix Converter
Converts arithmetic expressions into postfix notation.

### 🌐 NFA Visualizer
Displays Non-Deterministic Finite Automata using Graphviz.

### 🌳 DAG Visualizer
Shows Directed Acyclic Graph representation.

### ⚙️ LR(0) Parser Items
Displays LR(0) parsing items.

### 📂 Compiler Lab Files
Contains lab programs from **lab1.py** to **lab15.py**

---

## 📁 Modules Included

| Module Name | Description |
|------------|-------------|
| Lexical Analyzer | Token generation |
| FIRST & FOLLOW | Grammar set computation |
| Infix to Postfix | Expression conversion |
| NFA Visualizer | Automata graph |
| DAG Visualizer | Expression DAG |
| LR(0) Items | Parser item display |

---

## 📂 Project Structure

```bash
Compiler-Design/
│── app.py
│── first_follow.py
│── lr0.py
│── requirements.txt
│── README.md
│── lab1.py
│── lab2.py
│── lab3.py
│── ...
│── lab15.py


Compiler Lab Experiments
| No. | Experiment                   |
| --- | ---------------------------- |
| 1   | Lexical Analyzer             |
| 2   | Regular Expression to NFA    |
| 3   | NFA to DFA                   |
| 4   | Left Recursion Elimination   |
| 5   | Left Factoring               |
| 6   | FIRST and FOLLOW             |
| 7   | Predictive Parsing           |
| 8   | Shift Reduce Parsing         |
| 9   | LEADING and TRAILING         |
| 10  | LR(0) Items                  |
| 11  | Intermediate Code Generation |
| 12  | Quadruple / Triple           |
| 13  | Code Generation              |
| 14  | DAG Construction             |
| 15  | Storage Allocation           |



🛠️ Technologies Used
Python 3.x
Streamlit
Graphviz
Pandas


Learning Outcomes

After completing this project, students will understand:

✅ Tokenization process in compilers
✅ Grammar transformations
✅ Parsing strategies
✅ Automata conversions
✅ Intermediate code generation
✅ Structure of compiler front-end systems


Author

Eniya V

 License

This project is intended for academic and educational purposes.
