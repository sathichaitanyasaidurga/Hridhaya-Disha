# Heart Care Django Project

The Heart Care Django Project is a web application designed for heart disease hospitals to manage patient records, appointments, and medical information efficiently. This README file provides an overview of the project, installation instructions, and other relevant information.

## Features

**Appointment Scheduling**: Users can schedule appointments for patients, assign doctors, and manage the availability of doctors based on their schedule. The system also sends notifications to patients and doctors regarding upcoming appointments.

## Installation

To run the Heart Care Django Project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/sathichaitanyasaidurga
/Hridhaya-Disha.git`
2. Navigate to the project directory: `cd Heart-Care`
3. (Optional) Create and activate a virtual environment: `python3 -m venv myenv` and `source myenv/bin/activate`
4. Install the required dependencies: `pip install -r requirements.txt`
5. Set up the database by running migrations: `python manage.py migrate`
6. Create a superuser for accessing the admin panel: `python manage.py createsuperuser`
7. Start the development server: `python manage.py runserver`
8. Open a web browser and access the application at `http://localhost:8000`

Note: Make sure you have Python and Django installed on your system before proceeding with the above steps.

## Usage

Once the application is running, you can access the different features by navigating through the user interface. The application provides a user-friendly interface for scheduling appointments.

The admin panel can be accessed at `http://localhost:8000/admin`, where you can manage administrative tasks.


