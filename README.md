# Flask To-Do List

This is a simple to-do list application built with Flask, SQLite, and SQLAlchemy. The application allows users to create, view, update, and delete tasks.

## Features

- Create tasks: Users can create new tasks with a title and optional description.
- View tasks: Users can view their list of tasks, including the task title, description, and status.
- Update tasks: Users can update the status of a task (e.g., mark as completed).
- Delete tasks: Users can delete tasks they no longer need.

## Requirements

- Python 3.8 or higher
- Flask 2.0.1 or higher
- SQLite 3
- SQLAlchemy 1.4.0 or higher

## Installation


1. Clone the repository:
git clone https://github.com/your-username/flask-todo-list.git


2. Navigate to the project directory:
cd flask-todo-list


3. Create a virtual environment (optional but recommended):
python3 -m venv venv


4. Activate the virtual environment:
- For Unix/Linux:
  ```
  source venv/bin/activate
  ```
- For Windows:
  ```
  venv\Scripts\activate
  ```



5. Initialize the SQLite database:

python3
>>> from app import app, db

>>> app.app_context().push()

>>> db.create_all()


7. Start the application:

8. Open your web browser and navigate to `http://localhost:5000` to access the application.

## Configuration

- The configuration options can be found in the `config.py` file. You can modify the database configuration, secret key, and other settings as needed.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

