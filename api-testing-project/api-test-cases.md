# API Test Cases

API Endpoint:
https://jsonplaceholder.typicode.com/posts

TC-01
Scenario: Get all posts

Method:
GET

Expected Result:
Response status should be 200.

---

TC-02
Scenario: Get post by ID

Method:
GET

Endpoint:
/posts/1

Expected Result:
API returns post with ID 1.

---

TC-03
Scenario: Create new post

Method:
POST

Expected Result:
API should create a new resource and return status 201.
