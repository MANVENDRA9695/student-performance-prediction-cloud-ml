WEEK 1 — Requirements Freeze
Day 1
✅ Project Title freeze
SmartEdu AI: Cloud-Based Student Performance Prediction and Early Intervention System
Day 2
Introduction
Problem Statement
Day 3
Objectives
Scope
Day 4
Features / Modules finalization
Student module
Teacher module
Admin module
ML module
Data integration module
Day 5
External data sources finalization
College/LMS
GitHub
LeetCode
HackerRank
CSV/Excel import
Decide which sources will use API/OAuth/export
Day 6
Technology stack freeze
React
FastAPI
Python
PostgreSQL
Scikit-learn/XGBoost
SHAP
AWS
Docker/Git
Day 7

Week 1 review

# SmartEdu AI

### Cloud-Based Student Performance Prediction and Early Intervention System

## 📌 Week 1 — Project Foundation & Requirements

**Project Status:** Requirements & Planning Phase
**Phase:** Week 1
**Objective:** Define and freeze the project requirements, scope, modules, data sources, and technology stack before starting development.

---

## 1. Project Overview

SmartEdu AI is a cloud-based Machine Learning system designed to predict student academic performance, identify students who may be academically at risk, explain the factors influencing their performance, and provide personalized recommendations for improvement.

The system will combine academic information with permitted external learning and coding activity data to create a broader student performance profile.

---

## 2. Problem Statement

Traditional student performance monitoring mainly depends on examination results, attendance records, assignments, and manual observation.

This approach can make it difficult to identify struggling students at an early stage.

SmartEdu AI aims to provide an intelligent system that can:

* Predict expected student performance.
* Identify academically at-risk students.
* Determine important factors affecting performance.
* Provide personalized recommendations.
* Allow students to simulate possible performance improvements.
* Provide useful analytics to teachers and administrators.

---

## 3. Objectives

The main objectives of SmartEdu AI are:

1. Develop a Machine Learning model for student performance prediction.
2. Classify students into Low Risk, Medium Risk, and High Risk categories.
3. Develop an Early Warning System for academically at-risk students.
4. Implement Explainable AI to identify important prediction factors.
5. Generate personalized recommendations.
6. Develop a What-If Performance Simulator.
7. Provide separate dashboards for Students, Teachers, and Administrators.
8. Integrate academic and permitted external learning/coding data.
9. Store and manage data using cloud-based infrastructure.
10. Deploy the application using Amazon Web Services (AWS).

---

## 4. Project Scope

### 👨‍🎓 Student

The Student module will provide:

* Student profile
* Academic performance
* Attendance
* Assignment and examination information
* Coding activity
* Performance prediction
* Risk level
* Performance factors
* Personalized recommendations
* What-If simulator

### 👨‍🏫 Teacher

The Teacher module will provide:

* Student performance overview
* At-risk student identification
* Risk distribution
* Individual student analysis
* Academic performance trends

### 👨‍💼 Admin

The Admin module will provide:

* Student management
* Teacher management
* Institution-level analytics
* Prediction statistics
* Risk statistics
* Overall performance trends

---

## 5. Major Features / Modules

### 5.1 Authentication & User Management

* Login and registration
* Role-based access
* Student, Teacher, and Admin roles

### 5.2 Academic Data Management

* Attendance
* Internal marks
* Examination marks
* Assignments
* Previous GPA
* Backlogs

### 5.3 External Data Integration

The system will explore authorized data integration from:

* College/LMS platforms
* GitHub
* LeetCode
* HackerRank
* CSV/Excel imports

Official API, OAuth, institutional integration, or permitted export mechanisms will be preferred where available.

### 5.4 Machine Learning Prediction

The ML module will:

* Preprocess data
* Perform feature engineering
* Train multiple models
* Compare model performance
* Select the best-performing model
* Predict expected academic performance

### 5.5 Risk Detection

Students will be classified as:

* 🟢 Low Risk
* 🟡 Medium Risk
* 🔴 High Risk

### 5.6 Explainable AI

The system will explain the major factors influencing a prediction using techniques such as:

* SHAP
* Feature Importance

### 5.7 Personalized Recommendations

Recommendations may include:

* Improving attendance
* Completing pending assignments
* Increasing study hours
* Practicing weak subjects
* Taking regular mock tests

### 5.8 What-If Performance Simulator

Students will be able to modify selected factors and observe how the predicted performance changes.

Example:

```text
Current Attendance: 65%
Improved Attendance: 85%

Current Study Hours: 2 hours/day
New Study Hours: 4 hours/day

→ New predicted performance
```

### 5.9 Dashboards

Three major dashboards will be developed:

* Student Dashboard
* Teacher Dashboard
* Admin Dashboard

---

## 6. Technology Stack

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Backend

* Python
* FastAPI
* REST APIs

### Machine Learning

* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP

### Database

* PostgreSQL
* AWS RDS

### Cloud

* AWS EC2
* AWS RDS
* AWS S3

### DevOps

* Docker
* Git
* GitHub

---

## 7. Initial Project Structure

```text
SmartEdu-AI/
│
├── frontend/
├── backend/
├── ml/
├── database/
├── data/
├── docs/
├── tests/
└── README.md
```

---

## 8. Week 1 Deliverables

The following items are being finalized during Week 1:

* [x] Project title
* [x] Introduction
* [x] Problem statement
* [x] Objectives
* [x] Project scope
* [x] User roles
* [x] Major features/modules
* [x] External data source strategy
* [x] Technology stack
* [ ] System architecture
* [ ] ER diagram
* [ ] Database schema
* [ ] API design

The remaining system-design items will be completed in Week 2.

---

## 9. Current Development Status

**Phase:** Planning & Requirements
**Week:** 1
**Status:** 🟡 In Progress

### Next Phase

**Week 2 — System Design**

Planned work:

* System architecture
* User permissions
* ER diagram
* Database schema
* API structure
* UI/UX structure
* Development environment setup

       -------------------------------------------------------------------------------
