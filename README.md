# 🎓 School Dashboard System

## 📋 Project Overview
This is a comprehensive **school management system** built using **Next.js**. The application provides tailored dashboard views and functionality for different user roles: **admin, teacher, student, and parent**.

---

## 🧰 Core Technology Stack

- **Frontend**: Next.js (App Router pattern)  
- **Styling**: Tailwind CSS  
- **Database**: PostgreSQL with Prisma ORM  
- **Authentication**: Clerk  

---

## 🌟 Key Features

### 🧭 Dashboard Views
Role-based dashboards with distinct functionalities:

- **Teacher Dashboard** [`/teacher/page.tsx`] – Class schedule, announcements  
- **Admin Dashboard** [`/admin/page.tsx`] – School-wide statistics and management  

---

### 🗂️ Data Management
The system supports robust handling of core school entities:

- 👨‍🎓 Students  
- 👩‍🏫 Teachers  
- 🏫 Classes  
- 📘 Subjects  
- 📚 Lessons / Timetables  
- 📝 Assignments  
- 🧪 Exams  
- 📊 Grades / Results  
- 📅 Events  
- 📢 Announcements  
- 🧾 Attendance Records  

---

### 🧩 UI Components

- **📆 Calendar views** – Scheduling via `react-big-calendar`  
- **📈 Data Visualizations** – Built with Recharts:
  - Attendance charts  
  - Academic performance metrics  
  - Student demographics  
  - Financial reports  

---

## 🗃️ Database Structure (Prisma ORM)

The schema models real-world relationships:

- Teachers teach multiple subjects and manage classes  
- Students are assigned to classes and linked to parents  
- Classes have grade levels and supervising teachers  
- Lessons associate subjects, classes, and teachers  
- Exams and assignments relate to specific lessons  

---

## 🧑‍💻 User Interfaces

- 📋 Tabular views with search, filters, and pagination  
- 📝 Forms for creating, editing, and deleting records  
- 🖥️ Interactive dashboards with real-time updates  
- 🔐 Role-based access control for actions and views  

---

This school dashboard provides a complete, intuitive, and scalable solution for managing school operations, offering real-time data access and multi-role support through a modern tech stack.
