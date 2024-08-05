# Student Management System

A simple Student Management System built with Node.js, Express, and MongoDB. This application allows you to manage student records with basic CRUD operations.

## Features

- **View Students**: Fetch a list of all students.
- **Add Student**: Add a new student record.
- **Update Student**: Update an existing student record.
- **Delete Student**: Remove a student record.

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- MongoDB

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/student-management-system.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd student-management-system
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Setup MongoDB:**

    Ensure you have MongoDB installed and running on your local machine. The application connects to MongoDB using the default settings. You can change the connection string in the code if needed.

5. **Start the server:**

    ```bash
    npm start
    ```

6. **Access the application:**

    Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

## API Endpoints

### GET /api/students

Fetch all students.

**Response:**

```json
[
    {
        "_id": "student_id",
        "name": "Student Name",
        "age": 20,
        "grade": "A"
    }
]





