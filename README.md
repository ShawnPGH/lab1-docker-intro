# Lab 1: Introduction to Docker Containerization

## Objective
- Understand the basics of Docker containerization
- Create a Dockerfile
- Build a Docker image
- Run and verify a Docker container

## Requirements
- Docker Desktop installed (Windows / macOS / Linux)
- Basic knowledge of Python and command line

## Project Structure
```
lab1-docker-intro/
├── app.py
├── requirements.txt
└── Dockerfile
```

## How to Run

### 1. Build the Docker Image
```bash
docker build -t docker-lab1-app .
```

### 2. Run the Container
```bash
docker run docker-lab1-app
```

### Expected Output
```
Hello from Docker Container!
```

### 3. Cleanup (Optional)
```bash
# List running containers
docker ps

# Stop a container
docker stop <container_id>

# Remove container and image
docker rm <container_id>
docker rmi docker-lab1-app
```

## Guide Questions
1. What role does the Dockerfile play in containerization?
2. Why are Docker containers lighter than virtual machines?
3. What happens when the container finishes execution?
