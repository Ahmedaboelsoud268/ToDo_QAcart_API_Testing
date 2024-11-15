# ToDo QAcart API Testing

This repository contains tests for the ToDo QAcart API, focusing on the registration, login, and task management features. The tests utilize various HTTP request methods (GET, POST, PUT, DELETE) to ensure the functionality and reliability of the API endpoints.

## API Endpoints

- **Registration/Login URL**: `https://todo.qacart.com/api/v1/users/`
- **Tasks URL**: `https://todo.qacart.com/api/v1/tasks`

## Features Tested

- **User Registration**
- **User Login**
- **Task Management** (CRUD Operations)

## Environment Setup

1. **Environment Variables**:
   - Set the base URL for registration and login.
   - Define the tasks URL.
   - Create global variables for the authentication token.

2. **Authorization**:
   - The main folder uses Bearer token authentication.
   - Subfolders inherit authentication settings from the parent folder.

## Test Cases

Each test case checks the following parameters:

- **Response Body Parameters**: Validates the structure and data types.
- **Status Codes**:
  - `200 OK`
  - `201 Created`
  - `400 Bad Request`
  - `401 Unauthorized`
- **Response Time**: Ensures that the response time is acceptable.
- **Content Type**: Verifies the content type of the responses.
- **Schema Format**: Checks if the response adheres to the expected schema.

## Running Tests

To run the tests, follow these steps:

1. Open your terminal.
2. install newman to make report npm install -g newman.
3. Run the `TestRunner.bash` script by clicking on the TestRunner.bat:
4.Open the Todo_QA_report.html.
   #############################
