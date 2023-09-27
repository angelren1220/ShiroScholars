# ShiroScholars Learning Management System (LMS)

ShiroScholars is a Learning Management System designed by Ms. Shiro for her private teaching business. This platform aids in the effective management and delivery of educational content to students.

## Features

- User Authentication (teachers, students)
- Course Management (create, update, delete courses)
- Content Upload (videos, documents, links)
- Assignments & Grading
- Interactive Forums & Discussions
- Notifications & Announcements

## Tech Stack

- **Frontend**: Angular
- **Backend**: Django

## Getting Started

### Prerequisites

- Python (version 3.x recommended)
- Node.js and npm for Angular frontend

### Setting Up

1. **Clone the repository**:
    ```bash
    git clone git@github.com:angelren1220/ShiroScholars.git
    cd ShiroScholars
    ```

2. **Set up the virtual environment and install backend dependencies**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

3. **Navigate to frontend directory and install frontend dependencies**:
    ```bash
    cd shiroscholars-frontend
    npm install
    ```

### Running the Project

1. **Backend**:
    ```bash
    cd ShiroScholars
    source venv/bin/activate
    python manage.py runserver
    ```

2. **Frontend**:
    ```bash
    cd shiroscholars-frontend
    ng serve
    ```

Navigate to `http://localhost:4200` in your browser to access the LMS frontend, and the Django API will be running on `http://localhost:8000`.


