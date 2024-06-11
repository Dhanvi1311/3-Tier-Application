    +-----------------+       +-----------------+
    |                 |       |                 |
    |    Frontend     |<----->|    Backend      |
    |  (HTML, JS)     |       | (Python, Flask) |
    |                 |       |                 |
    +-----------------+       +--------+--------+
                                      |
                                      |
                                      v
                             +--------+--------+
                             |                 |
                             |   PostgreSQL    |
                             | (Database, GCP) |
                             |                 |
                             +-----------------+

# Objective
This project aims to develop a 3-tier web application with frontend, backend, and database connectivity. The application will be containerized using Docker and deployed on a Kubernetes cluster. Code versioning and collaboration will be managed through GitHub.

# Requirements
--Frontend: The user interface will be developed using HTML and JavaScript. <br />
--Backend: The backend will be a Python application using Flask to handle HTTP requests. <br />
--Database: Connectivity to a PostgreSQL database (GCP) will be implemented to store and manage data. <br />
--Docker: Each component (frontend, backend, database) will be containerized using Docker for consistency across different environments. <br />
--Deployment: The application will be deployed on a Kubernetes cluster for scalability and reliability.

# The application architecture consists of the following components:

## Frontend:

--HTML for structure and layout. <br />
--JavaScript for dynamic behaviour and interactivity. <br />

## Backend:

--Python Flask application for handling API requests and business logic. <br />
--Integration with Google Cloud services using service account credentials. <br />

## Database:

--PostgreSQL for persistent data storage. <br />
--Secure connection using credentials. <br />

## Containerization:

--Docker is used to create consistent runtime environments for the frontend and backend.

## Orchestration:

--Kubernetes for deploying, scaling, and managing the containerized application. <br />
