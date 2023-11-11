# Dockerized MongoDB, Express, and Node.js

This template serves as a robust starting point for building web applications using MongoDB, Express, and Node.js, all within Docker containers for ease of development and deployment.

## Features 🌟

- Docker and Docker Compose configuration for both development and production environments.
- Scalable project structure with Express.
- Pre-configured MongoDB connection.

## Prerequisites 📋

You'll need Docker and Docker Compose installed on your machine to use this project. Visit the official documentation to install [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/).

## Local Setup 🛠

To set up this project on your local development environment, follow these steps:

1. Clone this repository using git:

```bash
git clone https://github.com/codediaz/code-mongodb-nodejs.git
cd code-mongodb-nodejs
```

2. Create a .env file at the root of the project using the .env.example as a reference:

```bash
cp .env.example .env
```

3. Edit the .env file to set your environment variables.

4. Launch the project using Docker Compose:
```bash
docker-compose up --build
```
The application will be available at http://localhost:3000.

## Project Structure 📁
 - `app/`: Source code directory for the Node.js application.
- `Dockerfile`: Definitions for building the Docker image of the Node.js application.
- `docker-compose.yml`: Docker services configuration for development and production environments.
- `package.json`: Project metadata and dependencies.
- `.env.example`: Template for required environment variables.

## Deployment 🚀
For production deployment, ensure you configure your production environment with the appropriate environment variables and security settings. Consider using services like Docker Swarm or Kubernetes for a more robust and scalable deployment.

## Built With 🛠️
- [MongoDB](https://www.mongodb.com/es) - The NoSQL database for modern applications.
- [Express](https://expressjs.com/) - The web application framework for Node.js.
- [Node.js](https://nodejs.org/en) - The server-side JavaScript runtime environment.
- [Docker](https://www.docker.com/) - Containerization platform and services.

## License 📜
This project is open for public use and free to distribute under the terms of the MIT License. See the [LICENSE](https://github.com/codediaz/code-mongodb-nodejs/blob/main/LICENSE) file for details.

