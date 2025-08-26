# 🎓 Student Success SQL Project

## 📌 Project Description  
In today’s competitive educational environment, understanding what drives student success is more important than ever. Just like the transport system in a bustling city such as London must adapt to meet the needs of its residents, schools and educators must adapt to meet the diverse needs of students.  

This project analyzes a dataset containing detailed information about student life — including study habits, sleep patterns, attendance, tutoring sessions, and extracurricular activities — to uncover the factors that truly impact exam performance.  

Through a set of SQL queries, we explore:  
- Whether **studying more than 10 hours per week combined with extracurricular activities** improves exam performance.  
- The **“sweet spot” for study hours**, by grouping students into ranges (1–5, 6–10, 11–15, and 16+ hours) and comparing their average scores.  
- How to create a **privacy-preserving class ranking** using SQL window functions, where students see their relative position without exposing exact exam scores.  

---

## 🗂 Dataset  
**Table name:** `student_performance`  

| Column                     | Type    | Description                           |
|----------------------------|---------|---------------------------------------|
| `attendance`               | float   | Percentage of classes attended        |
| `hours_studied`            | integer | Weekly study hours                    |
| `extracurricular_activities` | varchar | Participation (`Yes` / `No`)          |
| `sleep_hours`              | float   | Average sleep per night (hours)       |
| `tutoring_sessions`        | integer | Tutoring sessions per month           |
| `teacher_quality`          | varchar | Teacher rating (`Low` / `Medium` / `High`) |
| `exam_score`               | float   | Final exam score                      |

---

## 🎯 Learning Goals  
- Apply **SQL aggregations** and `CASE` logic to segment data into meaningful groups.  
- Use **window functions** (`DENSE_RANK`) to assign fair, tie-sensitive student ranks.  
- Translate raw student-life data into **actionable insights** for teachers, students, and policymakers.  

---

## 🚀 Outcomes  
- Identify if **study hours + extracurriculars** correlate with higher performance.  
- Pinpoint the **optimal study-hour range** for maximizing exam scores.  
- Provide a **transparent but private student ranking system**. 
