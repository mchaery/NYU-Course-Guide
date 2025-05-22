# NYU Course Guide

A dynamic web application that helps NYU students explore, search, and evaluate courses using real student-generated feedback, ratings, and useful filters.

## 📌 Problem Overview

While selecting courses, students often face the following challenges:

- **PROBLEM 1**  
  Although professor evaluations exist, there is no access to **individual course reviews**, making it difficult to judge specific classes based on real student experience.

- **PROBLEM 2**  
  **Syllabi are not accessible** during registration, making it hard to evaluate grading policy, assignments, and attendance system.

- **PROBLEM 3**  
  Due to the **sheer volume and lack of structured information**, it's difficult to find courses that match a student's personal preferences and conditions.


---

## ⚙️ Tech Stack

- **Frontend**: React.js, Next.js  
- **Backend**: Next.js (API routes)  
- **Styling**: SASS, Material UI  

---

## 🔥 Features

### 🚪 Landing Page

- Shows curated course categories:
  - Top-Rated
  - Low-Difficulty
  - Department-specific courses

<p align="center">
  <img src="platformer/docs/landing.png" alt="Landing Page" width="400"/>
</p>

---

### 🔍 Search Page

- Filter courses by:
  - **Department**, **Professor**, **Credit count**
- Search with keywords (course title, professor name, etc.)
- Sort courses by:
  - **Rating**, **Difficulty**
- Click any course to view detailed info

<p align="center">
  <img src="platformer/docs/search.png" alt="Search Page" width="400"/>
</p>

---

### 📖 Course Detail Page

- View:
  - Overall rating
  - Course title, professor, and course description
- Write a review with comment and star rating
- See rating distribution graph
- Browse peer reviews

<p align="center">
  <img src="platformer/docs/detail.png" alt="Course Detail" width="400"/>
</p>

---

## Future Plans

- Connect to NYU’s real course API or internal dataset  
- Add user login and review history  
- Build a course recommendation chatbot that reflects each user’s interests  


