# API Test Cases

## Test Case 1: Retrieve All Users

Test Case ID: API_TC_01

Endpoint:
GET /users

Test Steps:
1. Send GET request to /users
2. Observe API response

Expected Result:
- Status code should be 200
- Response should contain user records
- Response format should be JSON


## Test Case 2: Validate User Data Structure

Test Case ID: API_TC_02

Endpoint:
GET /users

Test Steps:
1. Send GET request to /users
2. Inspect returned user object

Expected Result:
User object should contain:
- id
- name
- email


## Test Case 3: Invalid User Request

Test Case ID: API_TC_03

Endpoint:
GET /users/9999

Test Steps:
1. Send GET request with invalid user ID

Expected Result:
- Status Code should be 404 Not Found
