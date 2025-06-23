# 📰 NewsPortal Project - PHP & MySQL

A dynamic web-based **News Portal** developed using **PHP** and **MySQL**, featuring role-based access for:
- 🔐 **Admin**: Manages reporters, categories, news approvals, and system settings.
- ✍️ **Reporter**: Can create, edit, and submit news articles for approval.
- 👁️ **Reader**: Can view published news, search by category/date, and leave comments (if enabled).

---

## 🧑‍💻 Features

### 👑 Admin Panel
- Add/Edit/Delete reporters
- Approve or reject submitted news
- Manage news categories and site settings
- View user activity logs

### 📝 Reporter Dashboard
- Submit news articles with images
- Edit or delete own news
- View status of submitted articles

### 👀 Reader Portal
- Browse latest news
- Filter by category or date
- Read full articles
- Optional: Leave comments or share

---

## ⚙️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: PHP (Core PHP or MVC depending on your structure)
- **Database**: MySQL
- **Other Tools**: JavaScript, CKEditor (for article formatting)

---

## 🏗️ Database Setup

1. Import the SQL file (e.g., `newsportal.sql`) into your MySQL database:
   ```sql
   CREATE DATABASE newsportal;
   USE newsportal;
   -- then import your schema and data
