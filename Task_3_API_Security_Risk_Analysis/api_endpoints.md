# API Endpoints Evaluated

## Base URL

https://jsonplaceholder.typicode.com

## Tested Endpoints

### GET /posts

Purpose:
Retrieve available posts.

Risk Considerations:

* Excessive data exposure
* Lack of pagination

---

### GET /users

Purpose:
Retrieve user information.

Risk Considerations:

* Sensitive information exposure
* User enumeration

---

### GET /comments

Purpose:
Retrieve comment information.

Risk Considerations:

* Large data responses
* Information leakage

---

## Authentication Review

The selected demonstration API does not require authentication.

Potential Risk:
Unauthorized access to exposed resources.

Recommendation:
Implement OAuth 2.0, JWT, or API Key authentication.
