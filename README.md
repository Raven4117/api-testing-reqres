# API Testing Project – ReqRes Login

## Overview

This project demonstrates API testing of the login functionality using the ReqRes test API.

Base URL: https://reqres.in/api/login
Method: POST

## Tools Used

* Postman
* JMeter (optional, if you used it)
* Manual test case design

## Test Scenarios

* Valid login with correct credentials
* Invalid login with missing password
* Invalid login with incorrect credentials

## Test Cases

Detailed test cases are available in the `/test-cases` folder.

## How to Run

1. Import the Postman collection
2. Send POST request to `/api/login`
3. Verify response status and body

## Expected Results

* Status code 200 for valid login
* Status code 400 for invalid login
* Proper error messages returned

## Author

Dušan Krstić
