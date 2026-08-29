# student-management-yumul
# Student Management Application
## Student Information
Name: Yumul, Orland Andrew A.
Course/Section: BSIT Net AD CCIS-7E
## Project Description
This project is a simple Student Management Application
created using HTML, CSS, JavaScript, Node.js, and Express.js.
The application was developed and executed using
GitHub Codespaces.
## Features
- View students
- Add students
- Edit students
- Delete students
## Technologies Used
- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- GitHub
- GitHub Codespaces
## Cloud Networking
The application runs inside GitHub Codespaces.
The Node.js server listens on port 3000.
GitHub Codespaces forwards the application port so
that the web application can be accessed through
a browser.
## Cloud Security
Basic cloud security practices used in this activity include:
- No real student information was used.
- No passwords were stored in the source code.
- No API keys or credentials were committed.
- Port visibility was reviewed before sharing the application.
## Shared Responsibility Model
GitHub manages the underlying cloud infrastructure
used by GitHub Codespaces.
As the application developer, I am responsible for
the application code, repository access, credentials,
port configuration, and information stored or processed
by the application.
## Reflection Questions
### 1. What is the role of GitHub Codespaces in this activity?
It offers a writing, running and testing environment for the app in the browser, without the need to install any local application.
### 2. What is the purpose of port 3000?
The network port that the Express server is bound to, which allows the browser to send requests to and receive responses from the app.
### 3. What may happen when the application port is made public?
The forwarding of the URL meant that the app could be accessed from any internet connection and potentially been used without authorization or data being exposed.
### 4. Which parts of the environment are handled by GitHub
or the cloud provider?
Physical servers, data centers, underlying infrastructure, the Codespaces platform and physical networking.
### 5. Which parts are your responsibility as the
application developer?
Application code, access to the repository, data kept in the app, visibility of the port, credentials, configuration, and not having exposed secrets.
### 6. Why should passwords, API keys, and other secrets
not be uploaded to a public GitHub repository?
Exposed secrets are available in a public repo and may be stolen for use in gaining unauthorized access to an account or system.
### 7. How does this activity demonstrate the
Shared Responsibility Model?
The platform and infrastructure are taken care by GitHub, and my code, port settings and secrets are protected by me
