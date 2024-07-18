# Team-18
# Ekalavya Foundation Project

## Overview

The Ekalavya Foundation project is a comprehensive web application designed to support and manage the activities of a non-profit organization dedicated to education and mentorship. The project includes multiple dashboards for students, mentors, teachers, and administrators, each with specific functionalities to track progress, manage attendance, provide internship opportunities, link to live sessions, and more.

## Tech Stack

- **Backend**: Django, Express, Python, Mistral
- **Database**: PostgreSQL
- **Frontend**: HTML/CSS, JavaScript

## Features

- **Student Dashboard**: Progress tracker, attendance, internships, live sessions, course modules, profile management, assignments, fellowship options.
- **Mentor Dashboard**: Track mentee progress, schedule sessions, provide feedback.
- **Teacher Dashboard**: Manage course content, track student attendance, grade assignments.
- **Admin Dashboard**: User management, course management, analytics.

## Setup Instructions

#### Note: Please create your own database and enter the

### Clone the Repository

```
https://github.com/cfgmumbai24/Team-18.git
cd Team-18
```

## Setup the Backend
```
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
## Express:
```
sh
Copy code
cd express_backend
npm install
npm start
```
## Set Up the Frontend
## Ensure you have Node.js installed.
```
sh
Copy code
cd frontend
npm install
npm start
```

## Configure PostgreSQL
 Create a new PostgreSQL database and update the DATABASES setting in the Django settings.py file.

## Running Mistral (if applicable)
 Mistral is a workflow service. Ensure it is set up and running as per your environment requirements.

## Contribution Guidelines

 - Fork the repository
 - Create a new branch (git checkout -b feature-branch)
 - Commit your changes (git commit -m 'Add some feature')
 - Push to the branch (git push origin feature-branch)
 - Open a pull request

## Acknowledgements

The Django and Express communities for their excellent frameworks.
PostgreSQL for providing a robust and reliable database system.
The Ekalavya Foundation for the initiative and vision.
