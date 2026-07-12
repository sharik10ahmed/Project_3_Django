# Student Management System

A modest, yet capable web-based Student Management System built with Django. This application provides a streamlined interface for administrating student records, designed with simplicity and practical functionality in mind.

## 🚀 Features

- **Comprehensive Student Records:** Maintain detailed student profiles including name, class, contact information, date of birth, physical address, and profile imagery.
- **Robust Search & Filtering:** Quickly locate specific students using the search functionality (querying by name, ID, class, or address) and filter records based on the date they were added to the system.
- **Automated Email Notifications:** Automatically dispatch personalized welcome emails to students upon successful registration.
- **Data Pagination:** Effortlessly navigate through large volumes of student records with built-in pagination.
- **CRUD Operations:** Full Create, Read, Update, and Delete capabilities for complete data lifecycle management.

## 🛠️ Technology Stack

- **Backend:** Python, Django
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Database:** SQLite

## 📁 Project Structure

- `management_app/`: The core Django application containing models, views, urls, and core business logic.
- `school_management_system/`: The primary Django project configuration folder (settings, main urls).
- `templates/`: Contains all HTML templates styled with Bootstrap for a responsive user interface.
- `media/`: Directory designated for storing user-uploaded content (e.g., student profile images).

## ⚙️ Getting Started

### Prerequisites

- Python 3.x installed on your local machine.

### Installation

1. **Navigate to the project directory:**
   ```bash
   cd school_management_system
   ```

2. **Install dependencies:**
   Ensure Django is installed in your environment:
   ```bash
   pip install django
   ```

3. **Apply database migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

4. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
   The application will be accessible at `http://127.0.0.1:8000/`.

## ✉️ Email Configuration
To fully utilize the automated welcome email feature, ensure you configure the `EMAIL_BACKEND` and associated credentials (such as `EMAIL_HOST`, `EMAIL_PORT`, `EMAIL_HOST_USER`, and `EMAIL_HOST_PASSWORD`) in `school_management_system/settings.py` with your preferred SMTP server details.

---
*Developed with a focus on clean architecture and straightforward usability.*
