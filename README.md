My Blog Assignment

Project Overview
Welcome to MyBlog! This is a simple blog platform where you can read and create blog posts. The project is built using Django for the backend and HTML, CSS, and JavaScript for the frontend.

Project Setup
Requirements
Make sure you have Python installed on your computer. 
Getting Started
1) Clone the Repository:
    https://github.com/NisargBhavsar101/myblog.git
    cd myblog
2) Create a Virtual Environment:
    python -m venv venv
3) Activate the Virtual Environment:
    On Windows: venv\Scripts\activate
    On macOS/Linux: source venv/bin/activate
4) Install Dependencies:
    pip install -r requirements.txt
5) Run Migrations:
    python manage.py migrate
6) Start the Development Server:
    python manage.py runserver
Visit http://127.0.0.1:8000/ in your web browser to see the MyBlog homepage.
7) Run the following command to create a superuser:
    python manage.py createsuperuser
    You have to enter a username, email address, and password for the superuser. Follow the steps to complete the process.
* After creating the superuser, start the development server: 
    python manage.py runserver
-> Open your web browser and go to http://127.0.0.1:8000/admin/.
-> Log in using the credentials you provided during the superuser creation process.
-> Now, you should have access to the Django admin panel with your superuser account.

Commit History
    To demonstrate version control, here are some commits:  
    -> 28c5b61: It is initial commit for git setup with blog prooject and created Master Repository.
    -> 3c567ec: Made models and migrations with basic setup project.
    -> 1303c3e: Made views , urls and forms for blog post and merged it.
    -> 50c185b: Made templates and fix frontend-design and merge it.

Conclusion
    The MyBlog project is a simple and efficient blog platform developed with Django. Users can perform CRUD operations (Create, Read, Update, Delete) on blog posts. Follow the README instructions to set up the project