# AI-Driven Smart Classroom & Timetable Scheduler

An intelligent web-based timetable scheduling system designed to automate classroom allocation, faculty scheduling, and academic timetable generation using AI-inspired constraint-based scheduling techniques.

## 📌 Project Overview

Managing timetables manually in educational institutions often leads to:
- Scheduling conflicts
- Uneven faculty workload
- Inefficient classroom utilization
- Time-consuming administrative work

This project provides an automated and optimized timetable scheduling solution that generates conflict-free schedules for faculty, classrooms, and student batches.

---

## 🚀 Features

- Automated timetable generation
- Conflict-free scheduling
- Faculty-wise timetable view
- Classroom-wise timetable view
- Student dashboard
- Admin dashboard
- Dynamic classroom allocation
- Laboratory and theory subject handling
- Batch division support (G1/G2)
- Real-time schedule management
- Responsive web interface

---

## 🛠️ Technologies Used

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Deployment
- Vercel / Render / Netlify (Optional)

---

## ⚙️ System Modules

### 1. Admin Module
- Manage faculty
- Manage subjects
- Manage classrooms
- Generate timetables

### 2. Scheduling Engine
- Constraint-based scheduling
- Conflict detection
- Resource optimization

### 3. Database Module
- Store faculty data
- Store classroom data
- Store generated timetables

### 4. User Dashboard
- Student schedule view
- Faculty timetable access

---

## 🧠 Scheduling Logic

The scheduling engine:
1. Validates all input data
2. Prioritizes laboratory subjects
3. Checks faculty availability
4. Verifies classroom availability
5. Detects conflicts
6. Generates optimized timetable

---

## 📂 Project Structure

```bash
/client     -> Frontend React Application
/server     -> Backend Node.js API
/database   -> MongoDB Collections & Schemas
