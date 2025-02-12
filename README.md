# CGPA-Calculator

This application allows students to calculate their Cumulative Grade Point Average (CGPA) based on their course grades and credit hours. The project is built using Django, a powerful Python web framework.

## Features

- Calculate CGPA based on input grades and credit hours.
- Add, update, and remove courses and grades.
- View calculated CGPA and detailed report.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python (version 3.8 or above)
- pip (Python package installer)
- Django (version 4.0 or above)

## Getting Started

Follow these steps to set up and run the CGPA Calculator locally:

### 1. Clone the Repository

```bash
git clone https://github.com/aff057/Cgpa-Calculator.git
cd Cgpa-Calculator
```

### 2. Create a Virtual Environment

It is recommended to use a virtual environment to manage project dependencies.

```bash
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

Set up the database by applying migrations.

```bash
python manage.py migrate
```

### 5. Run the Development Server

Start the Django development server.

```bash
python manage.py runserver
```

Your application should now be running at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

## Usage

### Add Courses

1. Go to the "Add Course" page.
2. Enter the course name, credit hours, and grade.
3. Click "Submit" to save the course.

### Calculate CGPA

1. After adding courses, go to the "Calculate CGPA" page.
2. View your CGPA along with a detailed breakdown of your courses and grades.

### Update or Delete Courses

Navigate to the "Manage Courses" page to update or delete existing courses.

## Project Structure

```plaintext
cgpa_calculator/
├── cgpa_calculator/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── courses/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── manage.py
└── requirements.txt
```

- `cgpa_calculator/`: Contains the main project settings and configuration.
- `courses/`: Contains the app for managing courses and CGPA calculations.
- `manage.py`: Command-line utility for managing the project.
- `requirements.txt`: List of project dependencies.


