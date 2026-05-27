# Student Management Portal (Full-Stack CRUD Application)

A modern, full-stack student directory application built using a decoupled architecture. This project features a robust Python/Django REST API backend acting as a headless engine, connected to a highly responsive React frontend styled with Tailwind CSS.

## 🚀 Features
- **Full CRUD operations:** Create, Read, Update, and Delete students flawlessly from a single-page dashboard.
- **Strict Database Validation:** Managed via Django models requiring student names, class, stream, and exactly 5 compulsory subjects.
- **Reactive UI:** Instant table updates on creation, editing, or deletion without requiring manual page refreshes.
- **Dual-Pane Dashboard:** A responsive layout split into an intuitive data-entry form and a dynamic student directory.
- **Django Admin Integration:** Seamless data synchronization between the custom frontend UI and the native Django admin dashboard.

---

## 🛠️ Tech Stack

### Backend
- **Framework:** Django 5.x
- **API Toolkit:** Django REST Framework (DRF)
- **Database:** SQLite3
- **Security:** Django-CORS-Headers

### Frontend
- **Environment:** React 18+ (Vite)
- **Styling:** Tailwind CSS
- **State Management:** React Hooks (`useState`, `useEffect`, `useMemo`)

---

## 📂 Project Architecture

```text
django_prac/
├── student_portal/          # Django Backend Engine
│   ├── config/              # Project configuration (settings, URLs)
│   ├── students/            # Student App (models, views, serializers)
│   └── manage.py
│
└── student_frontend/        # React Frontend Application
    ├── src/                 # React Components & Assets
    ├── vite.config.js       # Vite development proxy configuration
    └── package.json
