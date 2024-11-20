#  Flask Login System



## Overview

Simple login system built using Flask and Flask-WTF forms. This project demonstrates a login page where users can enter their email and password to access the app. If the login credentials are correct, the user is redirected to a success page; otherwise, they are denied access.

## Features

- User authentication with email and password fields.
- **Flask-WTF** for handling form validation.
- **Bootstrap 5** for a responsive and clean design.

## Technologies Used

- **Flask** - A lightweight web framework for Python.
- **Flask-WTF** - A simple integration of **WTForms** with Flask.
- **Flask-Bootstrap** - Bootstrap 5 support for Flask applications.
- **WTForms** - Provides easy handling of forms.

## Installation Instructions

Before running the project, make sure to install the required packages.

### Step 1: Install Dependencies

Open the Terminal in PyCharm (bottom left). 

For **Windows**:

```bash
python -m pip install -r requirements.txt
```
For **MacOS**:

```bash
pip3 install -r requirements.txt
```
This will install the necessary packages from the requirements.txt file.
### 2. Step 2: Run the Flask Application
Once the dependencies are installed, run the following command to start the Flask server:
```bash
python app.py
```
The app will be hosted on http://127.0.0.1:5001.
## Code Explanation
- LoginForm: A class that defines the login form, which includes email and password fields.
- Routes:
  - /: The home route that renders the index.html template.
  - /login: The login page that handles user authentication.
  - If the email is admin@email.com and the password is 12345678, the user is redirected to the success page.
  - If the credentials are incorrect, the user is redirected to the denied page.
## Folder Structure
```bash
TinDog Project/
│
├── app.py                # Main Flask application file
├── templates/
│   ├── index.html        # Home page template
│   ├── login.html        # Login page template
│   ├── success.html      # Success page template
│   └── denied.html       # Denied page template
├── requirements.txt      # Required packages
└── README.md             # Project documentation
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.
## Acknowledgements
- Flask - For making web development easy and fun.
- Bootstrap 5 - For responsive design.
- Flask-Bootstrap - For easy Bootstrap integration.
