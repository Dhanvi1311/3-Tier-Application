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

#Objective
This project aims to develop a 3-tier web application with frontend, backend, and database connectivity. The application will be containerized using Docker and deployed on a Kubernetes cluster. Code versioning and collaboration will be managed through GitHub.

#Requirements
--Frontend: The user interface will be developed using HTML and JavaScript.
--Backend: The backend will be a Python application using Flask to handle HTTP requests.
--Database: Connectivity to a PostgreSQL database (GCP) will be implemented to store and manage data.
--Docker: Each component (frontend, backend, database) will be containerized using Docker for consistency across different environments.
--Deployment: The application will be deployed on a Kubernetes cluster for scalability and reliability.

#The application architecture consists of the following components:

##Frontend:

--HTML for structure and layout.
--JavaScript for dynamic behaviour and interactivity.

##Backend:

--Python Flask application for handling API requests and business logic.
--Integration with Google Cloud services using service account credentials.

##Database:

--PostgreSQL for persistent data storage.
--Secure connection using credentials.

##Containerization:

--Docker is used to create consistent runtime environments for the frontend and backend.

##Orchestration:

--Kubernetes for deploying, scaling, and managing the containerized application.
