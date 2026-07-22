# Click Grow Backend API
<img width="1506" height="1599" alt="WhatsApp Image 2026-07-22 at 3 50 22 PM" src="https://github.com/user-attachments/assets/20ddfb22-ca4c-4c58-b7f1-576ef2613e39" />


A Django-based backend application for the **Click Grow** ecosystem. This repository contains the core application settings, database configuration, ASGI/WSGI servers, and Python environment management for the service.

---

## 🛠️ Tech Stack & Requirements

*   **Language:** Python 3.14+
*   **Framework:** Django
*   **Interface:** ASGI (`asgiref`) & WSGI
*   **Virtual Environment:** `.venv`

---

## 🚀 Getting Started

Follow these instructions to set up the backend development environment on your local machine.

### 1. Prerequisites

Ensure you have Python installed on your system. You can verify your installation by running:

```bash
python --version
```

### 2. Clone the Repository

```bash
git clone <repository-url>
cd "Click Grow/Backend"
```

### 3. Set Up Virtual Environment

Create and activate an isolated Python virtual environment:

#### On macOS/Linux:
```bash
python -m venv .venv
source .venv/bin/activate
```

#### On Windows:
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 4. Install Dependencies

Install all required Python packages into your active virtual environment:

```bash
pip install -r requirements.txt
```

---

## 🏃 Running the Server

### Database Migrations

Before launching the server for the first time, apply the database migrations:

```bash
python manage.py migrate
```

### Development Server

Start the Django local development server:

```bash
python manage.py runserver
```

The server will start at `http://127.0.0.1:8000/`.

---

## 📁 Project Directory Structure

```text
Click Grow/
└── Backend/
    ├── .venv/               # Isolated Python Virtual Environment
    ├── .gitignore           # Git ignore rules for Backend
    ├── manage.py            # Django CLI management script
    └── Click_Grow/          # Main Project Configuration
        ├── __init__.py
        ├── settings.py      # App settings and configurations
        ├── urls.py          # Root URL routing
        ├── asgi.py          # Asynchronous Server Gateway Interface entry point
        └── wsgi.py          # Web Server Gateway Interface entry point
```

---

## 🧪 Testing

To run the automated test suite:

```bash
python manage.py test
```
>made with codex
>my Shivagangamma
