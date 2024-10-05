# Docker Simple Project
With the objective of learning and practicing Docker, a simple project was created that uses Docker to create a basic web server.

## Technologies Used
- **Flask**: Backend framework in Python.
- **MySQL**: Database for storing user data.
- **Nginx**: Web server for serving the frontend and proxying requests to the backend.
- **Docker**: Containerization tool for managing application components

## Getting Started
### Prerequisites
- Docker
- Docker Compose
### Running the Application
1. Clone the repository
```bash
git clone https://github.com/lufecrx/docker-simple-project.git
cd docker-simple-project
```
2. Build and start the application
```bash
docker-compose up --build
```
3. Access the application at: http://localhost:80
### Stopping the Application
```bash
docker-compose down
```
