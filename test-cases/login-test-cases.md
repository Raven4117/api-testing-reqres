Login API Test Cases
TC-01: Valid Login
Method: POST
Endpoint: /api/login
Body:
{
"email": "eve.holt@reqres.in",
"password": "cityslicka"
}
Expected Result:
Status: 200 OK
Token is returned
TC-02: Missing Password
Body:
{
"email": "eve.holt@reqres.in"
}
Expected Result:
Status: 400 Bad Request
Error: "Missing password"
