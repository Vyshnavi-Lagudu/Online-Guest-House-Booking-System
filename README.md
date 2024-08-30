# Resort Booking Website

A dynamic resort booking website built using Flask and SQLAlchemy. This project leverages object-oriented programming principles to provide a secure and user-friendly platform for managing resort reservations.

## Features

- **User Registration and Authentication:** Secure account creation and management with user login and registration.
- **Booking Management:** Users can view available resorts, make reservations, and manage their bookings.
- **Database Operations:** Utilizes Flask and SQLAlchemy for efficient tracking of resort availability and processing of bookings.
- **Advanced Functionalities:** Designed to streamline user interaction and improve the reservation process.

## Technologies Used

- **Backend:**
  - [Flask](https://flask.palletsprojects.com/en/2.0.x/): Web framework for Python.
  - [SQLAlchemy](https://www.sqlalchemy.org/): SQL toolkit and Object-Relational Mapping (ORM) library for Python.
  - [SQLite](https://www.sqlite.org/) or other databases if used.

- **Frontend:**
  - HTML/CSS/JavaScript for building the user interface.

- **Authentication:**
  - Flask extensions for user management and secure authentication.

  ## Usage

1. **Register an Account:** Access the registration page to create a new account.
2. **Log In:** Use your credentials to log in and manage your reservations.
3. **Browse Resorts:** View available resorts and check their availability.
4. **Make a Reservation:** Select a resort, choose your dates, and book a room.
5. **Manage Bookings:** View and manage your existing reservations from your user dashboard.

## Project Structure

- `app/`: Contains the main application code.
  - `models.py`: SQLAlchemy models for database interactions.
  - `routes.py`: Defines the routes and views.
  - `forms.py`: Contains forms used for user input.
  - `config.py`: Configuration settings for the Flask app.
  - `templates/`: Jinja2 templates for rendering HTML.
  - `static/`: Static files like CSS and JavaScript.

- `migrations/`: Directory for database migration scripts.

- `requirements.txt`: Lists the Python packages required for the project.