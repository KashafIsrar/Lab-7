# Lab-7
Cooking Chronicles is a Flask-based web application designed to help food enthusiasts explore, create, and share mouth-watering recipes. With a user-friendly interface and interactive features, the application aims to turn every meal into an unforgettable experience.

Features

Home Page: An inviting landing page introducing users to the platform.

About Us: Learn about the mission and vision behind Cooking Chronicles.

Recipes: Explore a treasure trove of diverse recipes and cooking tips.

Login and Registration: Join our community by creating an account or logging in.

Contact Us: Reach out for assistance or provide feedback.

Services Section: Learn about personalized recipe development, online cooking classes, and culinary inspiration.

Installation

Prerequisites

Python 3.8+

Flask Framework

A text editor or IDE (e.g., VS Code, PyCharm)

Steps

Clone this repository:

git clone https://github.com/username/cooking-chronicles.git

Navigate to the project directory:

cd cooking-chronicles

Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install the required dependencies:

pip install -r requirements.txt

Run the application:

python app.py

Open your browser and visit:

http://127.0.0.1:5000

Project Structure

Cooking-Chronicles/
|-- static/
|   |-- styles.css
|   |-- img/
|       |-- cooklogo.jpg
|       |-- cook3.jpeg
|       |-- cook4.jpeg
|       |-- food7.jpeg
|-- templates/
|   |-- home.html
|   |-- about.html
|   |-- recipies.html
|   |-- login.html
|   |-- registration.html
|   |-- contact.html
|-- app.py
|-- requirements.txt
|-- README.md

Key Files

app.py: The main Flask application file containing route definitions.

templates/: HTML templates for rendering pages.

static/: Static files like CSS, JavaScript, and images.
