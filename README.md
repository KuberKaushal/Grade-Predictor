

---

# 📊 Student Risk Predictor (C++)

## 📌 Overview

The **Student Risk Predictor** is a C++ console-based project that evaluates a student's academic risk level using performance metrics such as score, assignment completion, and attendance. It calculates a custom risk score and classifies students into categories like Low, Medium, or Critical Risk.

---

## ⚙️ Features

* Input validation and data clamping
* Object-oriented design using a class
* Weighted risk calculation using mathematical formulas
* Random noise factor to simulate real-world uncertainty
* Clear console-based output report

---

## 🧮 How It Works

The system computes a **risk metric** using:

* Score (weighted heavily using power function)
* Assignment count (reduces risk)
* Attendance (non-linear square root impact)

A small **random noise factor** is added to introduce variability, then thresholds determine the final risk category.

---

## 🛠️ Technologies Used

* C++
* Standard Libraries: `<iostream>`, `<cmath>`, `<cstdlib>`, `<ctime>`, `<string>`, `<vector>`

---

## ▶️ How to Run

1. Copy the code into a `.cpp` file (e.g., `risk_predictor.cpp`)
2. Compile:

   ```
   g++ risk_predictor.cpp -o predictor
   ```
3. Run:

   ```
   ./predictor
   ```

---

## 📥 Input

Currently uses **hardcoded sample data**:

* Student ID
* Score
* Assignments completed
* Attendance %

You can modify these values inside `main()`.

---

## 📤 Output

* Displays calculated risk metric
* Shows final classification:

  * Low Risk
  * Medium Risk
  * Critical Risk

---

## ⚠️ Notes

* Randomness means results may vary per run
* Designed for demonstration purposes, not real academic evaluation
* Debug output is intentionally included

---

## 🚀 Future Improvements

* Add user input support
* Store multiple student records
* Export results to file
* Improve risk model accuracy

---

## 👨‍💻 Author

Developed as a learning project to demonstrate C++ concepts and basic predictive modeling.
