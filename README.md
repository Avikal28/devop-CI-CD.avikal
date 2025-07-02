# Avikal_devops_project (23951A6625)

 DevOps project that demonstrates CI/CD using GitHub Actions and Docker with a simple Flask application.

## Features

- GitHub Actions CI/CD pipeline
- Dockerized Python (Flask) app
- Basic HTTP test using `curl`

## Getting Started

### Run Locally
```bash
docker build -t avikal-app .
docker run -p 5000:5000 avikal-app

