# Docker_Project_2_Complete-Application-Deployment-Using-Docker-Containers

## Project Overview
This project demonstrates how to deploy a complete application using Docker containers. It includes a frontend, backend, and database container, orchestrated using `docker-compose`.

## Technologies Used
- **Docker** for containerization
- **Flask** as the backend framework
- **PostgreSQL** as the database
- **Nginx** as the reverse proxy
- **React** for the frontend
- **Docker Compose** for container orchestration

## Implementation Plan
1. **Database Setup**
   - PostgreSQL container initialized with `init.sql`.
2. **Backend API**
   - Flask application running inside a Docker container.
3. **Frontend Application**
   - React application served via Nginx.
4. **Reverse Proxy with Nginx**
   - Routes frontend and backend requests.
5. **Docker Compose for Orchestration**
   - Manages multi-container deployment.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Mohamed-Akram26/Docker_Project_2_Complete-Application-Deployment-Using-Docker-Containers.git
   cd Docker_Project_2
   ```
2. Build and start the containers:
   ```bash
   docker-compose up --build
   ```
3. Access the application:
   - **Frontend:** `http://localhost`
   - **Backend API:** `http://localhost:5000`

## Stopping the Containers
```bash
docker-compose down
```
