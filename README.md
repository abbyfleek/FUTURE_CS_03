# FUTURE_CS_03
API Security Assessment – JSONPlaceholder
Project Overview

This project contains a security assessment of the JSONPlaceholder Test API. The purpose of the assessment is to identify common API security risks using publicly accessible endpoints while following responsible testing practices.

The assessment focuses on identifying vulnerabilities rather than exploiting them.

Target API

Base URL:

https://jsonplaceholder.typicode.com

JSONPlaceholder is a public REST API used for testing and prototyping applications.

Objectives

The assessment evaluates the API for the following security issues:

Open or unauthenticated endpoints

Excessive data exposure in API responses

Weak or missing authentication tokens

Authorization issues (accessing other users' data)

Missing rate limiting

Input validation issues

Tools Used

The following tools were used during the assessment:

Postman

Web Browser Developer Tools

Public API Documentation

These tools were used to send requests, inspect responses, and analyze potential security risks.

Tested Endpoints

The following endpoints were analyzed during the assessment:

/users
/users/{id}
/posts
/posts/{id}
/comments
/todos

These endpoints were tested using GET, POST, and PUT methods to observe how the API handles requests and responses.

Key Findings

The analysis revealed several common API security risks:

Open endpoints with no authentication

Exposure of user-related information

Missing authorization controls

Lack of rate limiting mechanisms

Weak input validation for POST and PUT requests

Although JSONPlaceholder is a demo API, these issues demonstrate the types of vulnerabilities that may exist in real-world APIs.

Ethical Considerations

This assessment was conducted on a public demo API designed for testing purposes.

No destructive actions or exploitation techniques were performed. The goal was solely to identify potential security risks and recommend improvements.

Project Structure
API-Security-Assessment/
│
├── API_Security_Report.pdf
├── README.md
├── postman_collection.json
└── screenshots/
     ├── users_endpoint.png
     ├── posts_endpoint.png
     ├── comments_endpoint.png
     └── todos_endpoint.png
Conclusion

This assessment highlights the importance of implementing strong security controls in REST APIs. Authentication, authorization, input validation, and rate limiting are essential to prevent unauthorized access and data exposure.
