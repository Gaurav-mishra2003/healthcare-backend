
🏥 Healthcare Backend – Assignment
This is a Django REST Framework-based backend system developed for a healthcare application as part of a hiring assignment.

It includes user registration, login, role-based access (Admin, Doctor, Patient), and APIs to manage doctors, patients, and assignments.

✅ Features Implemented
User Registration and Login using JWT (SimpleJWT)

Role-based access: Admin, Doctor, Patient

Admin can:

View/Create/Assign doctors and patients

Doctors can:

View their assigned patients

Patients can:

View their assigned doctors

PostgreSQL integration

Clean Django app structure

🛠️ Tech Stack
Framework: Django, Django REST Framework

Authentication: JWT (SimpleJWT)

Database: PostgreSQL

Language: Python

🚀 How to Run the Project Locally
1. Clone the Repository
git clone https://github.com/yourusername/healthcare-backend-assignment.git
cd healthcare-backend-assignment

3. Create and Activate Virtual Environment
python -m venv venv
source venv/bin/activate    # Linux/macOS
venv\Scripts\activate       # Windows

5. Install Dependencies
pip install -r requirements.txt

7. Set Up PostgreSQL
Create a PostgreSQL database and user

Configure database credentials in .env or settings.py

5. Run Migrations
python manage.py makemigrations
python manage.py migrate

7. Create Superuser (Admin)
python manage.py createsuperuser

9. Run the Development Server
python manage.py runserver
Copy
Edit
python manage.py runserver
