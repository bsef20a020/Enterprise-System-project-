# Enterprise-System-project
# Worklytics - Work Tracking System

Worklytics is a productivity analytics tool built with Ruby on Rails and PostgreSQL. It enables users to log their work hours, set weekly goals, and visualize productivity using beautiful charts. Admins can manage users, view logs, and export productivity reports.

---

## Tech Stack

- **Backend**: Ruby on Rails
- **Database**: PostgreSQL
- **Authentication**: Bcrypt  
- **Charts & Visualization**: Chartkick + Groupdate
- **Styling**: Bootstrap 5
- **Background Jobs**: Sidekiq (optional)
- **Data Generation**: Faker (for seed data)

---

## Features

###  User Functionality
- Sign up / login with secure password (bcrypt)
- Log work sessions (task, start & end time)
- Automatically calculates total hours
- Set weekly work goals
- View dashboard with:
  - Weekly logs
  - Progress vs goal (bar chart)
  - Weekly productivity trends

###  Admin Features
- Role-based access (admin/user)
- View all users and their logs
- Search, filter, and export reports as CSV
- Edit or remove incorrect entries

---
###  Task Status 

-Completed: Authentication, basic dashboard, models, UI
-Pending: time calculations, grouped charts, CSV export, seed data

