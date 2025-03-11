Django Authentication System
This project implements a Django-based authentication system designed to manage user registration, login, and profile management functionalities.

Features
User Registration: Allows new users to create accounts.
User Login: Enables existing users to log into their accounts.
Profile Management: Users can view and update their profile information.

Project Structure
The repository is organized as follows:
myproject/: Contains the main project settings and configurations.
onlinecourse/: Houses the core application logic related to the authentication system.
static/: Includes static files such as CSS and JavaScript.
db.sqlite3: SQLite database file storing application data.
manage.py: Command-line utility for administrative tasks.
requirements.txt: Lists the Python dependencies required for the project.
runtime.txt: Specifies the Python runtime environment.

Technologies Used
Django: High-level Python web framework.
SQLite: Lightweight database for development and testing.
HTML/CSS/JavaScript: Frontend technologies for the user interface.

Getting Started
To set up the project locally, follow these steps:

Clone the repository:
git clone https://github.com/HSk2703/Django-Auth-System.git

Navigate to the project directory:
cd Django-Auth-System

Create a virtual environment:
python -m venv env

Activate the virtual environment:
On Windows:
env\Scripts\activate

On macOS/Linux:
source env/bin/activate

Install the dependencies:
pip install -r requirements.txt

Apply migrations:
python manage.py migrate

Run the development server:
python manage.py runserver

Access the application: Open your web browser and navigate to http://127.0.0.1:8000/.

Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

License
This project is licensed under the MIT License. See the LICENSE file for details.
