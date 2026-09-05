  GNU nano 8.7.1                                                                                        README.md *
# Node.js Docker Assignment

## Project Overview

This project demonstrates how to build, containerize, and deploy a simple Node.js application using GitHub, Docker, Docker Hub, and an Ubuntu Linux server on AWS EC2.

## Technologies Used

- Node.js
- Express.js
- Git & GitHub
- Docker
- Docker Hub
- Ubuntu (AWS EC2)

## Project Structure

```text
docker-assignment/
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
├── .gitignore
└── README.md
```

## Build the Docker Image

```bash
docker build -t mistajerry14/nodejs-app:1.0 .
```

## Run the Docker Container

