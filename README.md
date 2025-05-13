# Sliding-Puzzles

# Student Progress Tracker 🎓

This project is a **Student Progress Tracker** that evaluates students' academic progress based on their credit scores in pass, defer, and fail categories. The system categorizes students into different outcomes and provides a histogram representation.

---

## 📌 Overview

- Validates user input to ensure correct credit entry
- Categorizes students based on pass, defer, and fail credits
- Displays real-time results and outcome histogram
- Saves outcomes to a file
- Uses a dictionary to store individual student records

---

## ✨ Features

### ✅ User Input Validation
- Accepts only integers
- Accepts only valid credit values: `0`, `20`, `40`, ..., `120`

### 🎯 Categorization of Student Progress
- **Progress**: 120 pass credits  
- **Progress (Module trailer)**: 100 pass credits  
- **Module retriever**: 60 or 80 pass credits  
- **Exclude**: 80 or more fail credits

### 💾 Data Storage & Output
- Displays results in real-time
- Generates a vertical histogram of outcomes
- Saves results in `20222163_shakinya.txt`
- Uses a Python dictionary (`student_dict`) to store all student records

---

## 🛠️ Installation & Setup

### ✅ Prerequisites
- Python 3.x installed

### ▶️ Running the Program
```bash
# Clone the repository
git clone https://github.com/yourusername/student-progress-tracker.git

# Navigate into the project folder
cd student-progress-tracker

# Run the tracker script
python progress_tracker.py

