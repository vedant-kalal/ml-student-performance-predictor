# 🎓 Student Performance Analysis using Machine Learning

This project analyzes student academic performance based on various lifestyle, behavioral, and academic factors. It uses a dataset of students with features like study hours, stress level, use of educational technology, and more to predict the **Final Grade**.

---

## 📁 Project Structure

student-performance-project/
├── data/ # Contains the CSV dataset
├── jupyter notebooks/ # Jupyter Notebooks with EDA and ML
├── Output/ # Output CSVs, evaluation results
├── README.md # This file
├── requirements.txt

---

## 📊 Dataset Overview

The dataset contains the following columns:

- `Student_ID`  
- `Age`  
- `Gender`  
- `Study_Hours_per_Week`  
- `Preferred_Learning_Style`  
- `Online_Courses_Completed`  
- `Participation_in_Discussions`  
- `Assignment_Completion_Rate (%)`  
- `Exam_Score (%)`  
- `Attendance_Rate (%)`  
- `Use_of_Educational_Tech`  
- `Self_Reported_Stress_Level`  
- `Time_Spent_on_Social_Media (hours/week)`  
- `Sleep_Hours_per_Night`  
- `Final_Grade` (Target Variable)

---

## 📌 Objective

To explore and model the relationship between lifestyle/academic habits and student grades using machine learning classification algorithms.

---

## ⚙️ Features Used

After preprocessing, these features were used:

- `Study_Hours_per_Week`
- `Online_Courses_Completed`
- `Assignment_Completion_Rate (%)`
- `Exam_Score (%)`
- `Attendance_Rate (%)`
- `Time_Spent_on_Social_Media (hours/week)`
- `Sleep_Hours_per_Night`
- Encoded categorical features like:
  - `Gender`
  - `Preferred_Learning_Style`
  - `Participation_in_Discussions`
  - `Use_of_Educational_Tech`
  - `Self_Reported_Stress_Level`

---

## 📈 Visualizations

All charts and graphs (like correlation heatmaps, feature importance, confusion matrices, etc.) are saved in the `/Output` folder.

---

Made by [Vedant Kalal]