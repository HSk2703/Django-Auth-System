Django Authentication System
This project implements a Django-based authentication system designed to manage user registration, login, and profile management functionalities.

Features
User Registration – Allows new users to create accounts.
User Login – Enables existing users to log into their accounts.
Profile Management – Users can view and update their profile information.
Project Structure
The repository is organized as follows:

php
Copy code
Django-Auth-System/
│── myproject/          # Main project settings and configurations
│── onlinecourse/       # Core authentication app
│── static/             # Static files (CSS, JavaScript, images)
│── db.sqlite3          # SQLite database
│── manage.py           # Django management script
│── requirements.txt    # Project dependencies
│── runtime.txt         # Python runtime environment
Technologies Used
Django – High-level Python web framework
SQLite – Lightweight database for development and testing
HTML, CSS, JavaScript – Frontend technologies for UI
Getting Started
To set up the project locally, follow these steps:

1. Clone the Repository
bash
Copy code
git clone https://github.com/HSk2703/Django-Auth-System.git
cd Django-Auth-System
2. Create and Activate a Virtual Environment
bash
Copy code
python -m venv env
On Windows:

bash
Copy code
env\Scripts\activate
On Mac/Linux:

bash
Copy code
source env/bin/activate
3. Install Dependencies
bash
Copy code
pip install -r requirements.txt
4. Apply Migrations
bash
Copy code
python manage.py migrate
5. Run the Development Server
bash
Copy code
python manage.py runserver
6. Access the Application
Open your web browser and go to:
👉 http://127.0.0.1:8000/

Contributing
Contributions are welcome! If you'd like to contribute:

Fork the repository
Create a feature branch
Submit a pull request
License
This project is licensed under the MIT License. See the LICENSE file for details.

