My Python Web Development
Django Lab Work — Learning Repository
Purpose
This project is a hands-on Django web development lab designed for beginners and intermediate developers. It is a real working example that covers core Django concepts through practical, readable code.
Whether you are just starting with Django or looking to sharpen your skills, you will find working examples of the most important concepts in web development with Python.

Technologies Used
•	Python 3.x
•	Django (Web Framework)
•	SQLite (Default Database for development)
•	HTML5 / CSS3 (Templates & Styling)

What You Will Learn From This Project
Topic	What is Covered
Models & Database	How to define data models and work with the database
Views & Templates	How Django handles pages and renders HTML
Forms	How to collect and validate user input
Authentication	How to handle login, logout, and user sessions

Project Structure
My-Python-Software-Development/
├── README.md                   ← You are here
├── requirements.txt            ← All packages needed
├── .gitignore                  ← Files excluded from repo
├── manage.py                   ← Django's command-line tool
├── myproject/                  ← Project configuration
│   ├── settings.py             ← Global settings
│   ├── urls.py                 ← Main URL routing
│   └── wsgi.py
├── myapp/                      ← Main application
│   ├── models.py               ← Database models
│   ├── views.py                ← Page logic
│   ├── forms.py                ← Form definitions
│   ├── urls.py                 ← App-level routing
│   └── templates/myapp/        ← HTML templates
├── static/css/style.css        ← Stylesheets
└── docs/getting-started.md     ← Learning notes

How To Set Up and Run This Project
Follow these steps carefully. They are written for complete beginners.

Step 1 — Clone the Repository
git clone https://github.com/gilleshJ/My-Python-Software-Development.git
cd My-Python-Software-Development

Step 2 — Create a Virtual Environment
On Windows:
python -m venv venv
venv\Scripts\activate
On Mac/Linux:
python3 -m venv venv
source venv/bin/activate

Step 3 — Install Required Packages
pip install -r requirements.txt

Step 4 — Apply Database Migrations
python manage.py migrate

Step 5 — Create an Admin User (optional but recommended)
python manage.py createsuperuser

Step 6 — Run the Development Server
python manage.py runserver
Then open your browser and go to: http://127.0.0.1:8000

Environment Variables
This project uses a .env file to store sensitive information like the secret key. Never share your .env file publicly.
Create a .env file in the root folder with the following:
SECRET_KEY=your-secret-key-here
DEBUG=True

Author
gilleshJ
GitHub: https://github.com/gilleshJ

Contributing
This is a learning repository. Feel free to:
•	Fork it and experiment
•	Open issues if you find bugs or have questions
•	Submit pull requests if you want to improve the examples

License
This project is open source and available under the MIT License.

Tip for learners: Read the code slowly. Check each file, understand what it does, then try to modify something small and see what happens. That is the best way to learn!
# My-Python-Software-Development
