# Django Simple Chat Application
Welcome to the Django Simple Chat Application repository! This project is a basic chat application built using Django, designed to demonstrate a straightforward implementation of real-time messaging functionality in a web application.

## About This Project
The Django Simple Chat Application offers a basic platform for users to register, log in, and engage in text-based conversations. It's an excellent starting point for anyone looking to understand the fundamentals of building chat features in web applications using Django.

## Key Features
- User registration and login system
- Real-time text messaging
- Simple and intuitive user interface
- Installation and Setup
- To get this application running on your local machine, follow these steps:

## Prerequisites
Ensure you have Python installed on your machine. This application requires Python 3.x.

## Installation
Clone the Repository

First, clone this repository to your local machine using:

```
git clone https://github.com/[YourUsername]/django-simple-chat-app.git
Create a Superuser
```

Navigate to the project directory and run the following command to create a superuser:

```
python manage.py createsuperuser --username [username] --email [email]
## Follow the prompts to set a password for the superuser.

Run Migrations
```
Initialize the database by running:

```
python manage.py migrate
```
Start the Server

Start the local development server using:

```
python manage.py runserver
```
Accessing the Application
Open your web browser and go to 127.0.0.1:8000/login.
Log in using the superuser credentials you created.
Start chatting!
Contributing
Contributions to enhance this simple chat application are welcome. Feel free to fork the repository and submit pull requests.

