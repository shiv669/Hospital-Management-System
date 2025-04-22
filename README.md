# Hospital Management System

## Features

### Admin
- Manage doctor registrations and approvals.
- Handle patient admissions and discharges.
- Generate and download invoices.
- Manage appointments.

### Doctor
- Apply for a job and manage patient details.
- View discharged patients and appointments.

### Patient
- Create an account and manage appointments.
- View assigned doctor details and download invoices.

---

## How to Run This Project

1. **Install Requirements:**
   - Ensure Python 3.7.6 is installed (check "Add to Path" during installation).
   - Open a terminal and execute the following commands:
     ```bash
     pip install django>=4.2,5.0
     pip install django-widget-tweaks
     pip install xhtml2pdf
     pip install sqlparse
     pip install reportlab
     ```

2. **Setup Project:**
   - Download and extract the project zip folder.
   - Navigate to the project folder in the terminal:
     ```bash
     cd to the directory where manage.py file is there 
     ```

3. **Database Migrations:**
   - Run the following commands to set up the database:
     ```bash
     python manage.py makemigrations
     python manage.py migrate
     ```

4. **Start the Server:**
   - Run the server with:
     ```bash
     python manage.py runserver
     ```

5. **Access the Project:**
   - Open your browser and go to:
     ```
     http://127.0.0.1:8000/
     ```




