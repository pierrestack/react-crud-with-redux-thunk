# CRUD Students Application

## Description
This application is a CRUD (Create, Read, Update, Delete) interface for managing students. It is developed in React with Redux and uses `redux-thunk` for handling asynchronous actions. A simulated backend with `json-server` is used to interact with a JSON database.

## The project is divided into two main folders:
The project is divided into two main folders:
- **frontend** : Contains the React source code.
- **backend** : Contains the `db.json` file used by `json-server` to simulate a REST API.

## Prerequisites
- Node.js (version 12+)
- npm ou yarn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/pierrestack/react-crud-with-redux-thunk.git
    cd react-crud-with-redux-thunk

    ```

2. Install dependencies for the frontend:
    ```bash
    cd frontend
    npm install
    ```

3. Install `json-server` to simulate an API:
    ```bash
    npm install -g json-server
    ```

## Execution

### Frontend
In the `frontend` folder, run the following command to start the React application:
```bash
npm start
```

### Backend
In the `backend` folder, start the JSON server by running the following command:
json-server --watch db.json --port 5000

The API will be accessible at the following address: `http://localhost:5000/students`.

## Features
- **Add a student**: Add a new student to the database.
- **View students**: List all students.
- **Edit a student**: Modify an existing student's information.
- **Delete a student**: Remove a student from the database.

## Technologies Used
- **React**: For building the user interface.
- **Redux**: For managing the global application state.
- **Redux-thunk**: For handling asynchronous actions.
- **json-server**: To simulate a REST API

## Notes
- The `db.json` file serves as the JSON database for students.
- Ensure that both the JSON server and the React application are running simultaneously for the app to work correctly.

## Authors
**ANDRIANARIVO Pierre Emmanuel**
