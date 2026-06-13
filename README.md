# DevOps Project: Flask Application with PostgreSQL
Built using Python 3.9, Flask micro-framework, and PostgreSQL 15.
This repository contains a containerized Python Flask application integrated with a PostgreSQL database, featuring an automated CI/CD pipeline.

## Features
- **Flask Web App**: Provides routing for home, health checks, and database connection tests.
- **PostgreSQL Database**: Persistent relational database container.
- **Dockerized**: Fully containerized using a custom Dockerfile and orchestrated via Docker Compose.
- **CI/CD Pipeline**: Automated linting and unit testing powered by GitHub Actions.

## Getting Started Locally

### Prerequisites
Make sure you have Docker and Docker Compose installed on your local machine.

### Running the Application
To spin up the multi-container environment, run:
```bash
docker-compose up --build
## Environment Configurations
The application securely handles database credentials using internal Docker environment mappings.
## License
This academic DevOps project is distributed under the MIT License.
## Port Allocations
- Web App: Container Port 5000 mapped to Host Port 5000
- Database: Container Port 5432 mapped to Host Port 5432
## Code Standards
Code linting rules are strictly enforced following PEP 8 style guides via Flake8.
## Project Status
Production setup verified, pipeline operational, and ready for submission.