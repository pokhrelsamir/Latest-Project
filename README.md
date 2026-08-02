# AcadStat — Student Result and Performance Analysis System

A comprehensive **AcadStat — Student Result and Performance Analysis System** built with **Django** for managing students' records and study academic performance .

---

## Features

- 🔐 User Authentication & Role-Based Access
- 👨‍🎓 Student Management
- 👨‍🏫 Teacher Management
- 📚 Subject & Semester Management
- 📝 Marks & Result Management
- 📄 Student Mark Sheet Generation
- 📊 Performance Analytics & Reports
- 📈 Dashboard with Statistics
- ⚙️ Django Admin Panel

---

## Documentation

> **Complete project workflow and documentation are available in:**

```text
docs/Workflow.md
```

---

## Project Structure

```text
djangoacadstat/
│
├── environment/                  # Virtual environment and dependency files
│   ├── requirements.txt
│   ├── setup_venv.bat
│   ├── setup_venv.sh
│   ├── .env.example
│   └── venv/
│
├── academicsys/                  # Django project configuration
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── core/                         # Main Django application
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── migrations/
│   ├── management/
│   ├── templates/
│   └── static/
│
├── static/                       # Global static assets
├── media/                        # User uploaded files
│
├── data/                         # Database backups and exported files
│   └── backups/
│
├── samples/                      # Sample files and templates
│   └── bulk_marks_upload/
│
├── scripts/                      # Utility scripts
│   ├── setup/
│   ├── debug/
│   └── patches/
│
├── docs/                         # Documentation
│   ├── Workflow.md
│   └── commands/
│
├── manage.py
└── README.md
```

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| Django 5.x | Backend Framework |
| PostgreSQL | Database |
| HTML5 | Frontend |
| CSS3 | Styling |
| JavaScript | Client-side Functionality |
| Bootstrap | Responsive UI |
| Chart.js | Data Visualization |

---

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/acadstat.git
cd acadstat
```

---

### 2. Create the Virtual Environment

#### Windows

```bat
environment\setup_venv.bat
environment\venv\Scripts\activate
```

#### Linux/macOS

```bash
chmod +x environment/setup_venv.sh
./environment/setup_venv.sh
source environment/venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r environment/requirements.txt
```

---

### 4. Configure Environment Variables

Copy the example configuration file:

```bash
cp environment/.env.example .env
```

Update the required environment variables before running the project.

---

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

---

### 6. Create an Administrator Account

```bash
python manage.py createsuperuser
```

---

### 7. Run the Development Server

```bash
python manage.py runserver
```

---

### 8. Open the Application

```text
http://127.0.0.1:8000/
```

---

## Database Models

| Model | Description |
|--------|-------------|
| Student | Student profile and academic information |
| Teacher | Faculty information |
| Department | Academic departments |
| Semester | Semester records |
| Subject | Subject information |
| Result | Student marks and grades |
| Attendance | Attendance records |
| User | Authentication and role management |

---

## Project Directories

| Directory | Purpose |
|-----------|---------|
| `environment/` | Virtual environment, dependencies, and configuration |
| `academicsys/` | Django project configuration |
| `core/` | Main application containing business logic |
| `static/` | Shared CSS, JavaScript, and images |
| `media/` | Uploaded files |
| `data/` | Database backups and exported reports |
| `samples/` | Sample files for bulk uploads |
| `scripts/` | Setup, maintenance, and debugging scripts |
| `docs/` | Project documentation |

---

## Documentation

The project documentation includes:

- Installation Guide
- Workflow Documentation
- Development Commands
- Project Architecture
- Database Design
- Deployment Guide

See:

```text
docs/Workflow.md
```

---

## Screenshots

You can add screenshots after completing the project.

```text
screenshots/
├── login.png
├── dashboard.png
├── students.png
├── marks.png
├── attendance.png
└── reports.png
```

---

## Future Improvements

- Django REST Framework API
- AI-Based Student Performance Prediction
- QR Code Attendance
- Email Notifications
- PDF Report Generation
- Excel Import & Export
- Parent Portal
- Mobile Responsive Dashboard

---

## License

This project is developed for educational purposes and is free to use and modify.

---

## Author

**Samir Pokhrel**

B.Sc. CSIT Student  
Tribhuvan University
