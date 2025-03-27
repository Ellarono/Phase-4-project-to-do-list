# To Do List App

A simple and efficient web application to manage your tasks. This app is built using Flask and SQLAlchemy on the backend and provides a clean interface for users to add, complete, and delete tasks.

## Features

- **Add Tasks**: Users can add new tasks to their to-do list.
- **Mark Tasks as Complete**: Toggle tasks between completed and incomplete states.
- **Delete Tasks**: Remove tasks from the list once they are no longer needed.
- **Task Persistence**: Tasks are stored in a SQLite database to ensure data persistence.

---

## Installation and Setup

### Prerequisites

- Python 3.7+
- Flask
- Flask-SQLAlchemy

### Steps to Run the Application Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
2. **Set Up a Virtual Environment**:
   ```bash
    python -m venv venv
   source venv/bin/activate  # On Windows: venv\scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Initialize the Database**:
    ```bash
   flask shell
   >>> from app import db
   >>> db.create_all()
   >>> exit()
   ```
5. **Run the Application**:
   ```
   python app.py
   ```
   This will open your app in the browser
## Technologies Used
**Frontend**: HTML, CSS (via Flask's Jinja2 templating engine)

**Backend**: Python, Flask

**Database**: SQLite (via Flask-SQLAlchemy)

## Usage
**Add a Task**
Enter a task title in the input field on the homepage and click the "Add Task" button.

**Mark a Task as Complete**
Click on a task's "Mark as Complete" button to toggle its completion status.

**Delete a Task**
Click on the "Delete" button next to a task to remove it permanently from the list.


## License
This project is licensed under the MIT License. See the LICENSE file for details.



