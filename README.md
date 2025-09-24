# Youngdev_internship_Tasks

# Python 

A structured collection of Python programs to build your skills from beginner to intermediate level with hands-on exercises and a mini project.

---

## Overview

This repo is organized into three main tasks, each targeting specific Python concepts:

- **Task 1: Basic Python Programs**  
- **Task 2: Intermediate Python Tasks**  
- **Task 3: Mini Python Project**

---

## Task 1 – Basic Python Programs  
**Objective:** Build a strong foundation in Python programming by solving beginner-friendly problems.

### Key Features:  
- Practice with loops and conditionals  
- Work with string manipulation and numeric computations  
- Implement simple mathematical algorithms  
- Learn user input handling and basic functions  

### Programs Included:  
- Fibonacci sequence generator  
- Prime number checker  
- String reversal  
- Basic calculator (addition, subtraction, multiplication, division)  
- Factorial calculation  

---

## Task 2 – Intermediate Python Tasks  
**Objective:** Advance your Python skills by working with data structures, modular design, file operations, and OOP.

### Key Features:  
- Use lists and dictionaries for data processing  
- Write reusable functions and modules  
- Perform file input/output operations for data persistence  
- Understand classes and objects to model real-world entities  

### Sample Tasks:  
- Word frequency counter using dictionaries  
- Simple math library with functions and modules  
- Reading and writing student records using file handling  
- Creating and using classes like Student or Bank Account  

---

## Task 3 – Mini Python Project (Python Quiz Game)
**Objective:** Integrate your knowledge by creating a practical application that simulates a real-world scenario.

### Key Features:  
- Design interactive user interfaces with console input/output  
- Manage program flow using control structures  
- Implement scoring and feedback systems  
- Combine multiple concepts: functions, loops, conditionals, and data structures  

# Python Quiz Game

An interactive multiple-choice quiz game built with Python.  
This project showcases object-oriented programming, file handling, user input validation, and text-to-speech feedback using the `pyttsx3` library.

---

## Key Features

- **Multiple-choice questions:** Presents each question with four answer options (A, B, C, D).  
- **Clean OOP design:** Uses `Question` and `QuizGame` classes for modular and maintainable code.  
- **Load questions from file:** Easily add or modify quiz questions by editing an external text file (`questions.txt`).  
- **User input validation:** Ensures only valid answer options are accepted.  
- **Score tracking and detailed results:** Shows total correct and incorrect answers, percentage score, and personalized feedback messages.  
- **Text-to-speech integration:** Uses `pyttsx3` to provide voice feedback during the quiz for enhanced user engagement.  

---

## How It Works

- Questions are stored in a text file with the following format per question block (6 lines each):

  1. Question prompt  
  2. Option A (e.g., `A) Option text`)  
  3. Option B  
  4. Option C  
  5. Option D  
  6. Correct answer letter (A, B, C, or D)  

- The quiz reads these questions, presents them one-by-one, collects and validates user input, and keeps track of the score.  
- After completing all questions, it displays the results and speaks encouraging messages based on the performance.  

---

## Usage Instructions

### Prerequisites

- Python 3.x installed on your machine.  
- Install the `pyttsx3` library for text-to-speech support:  
  ```bash
  pip install pyttsx3


