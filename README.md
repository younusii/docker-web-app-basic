# Dockerized Web Application

A simple static website served using Nginx inside a Docker container.

## Technologies
- Linux
- Docker
- Dockerfile
- Nginx
- HTML and CSS

## Features
- Lightweight Nginx Alpine image
- Custom HTML website
- Containerized web server
- Port mapping to access the website locally

## Run Locally

Build the Docker image:

```bash
docker build -t my-devops-website .
```

Start the container:

```bash
docker run -d --name devops-website -p 8080:80 my-devops-website
```

Open `http://localhost:8080` in your browser.

## Stop the Container

```bash
docker stop devops-website
```

## Purpose

This project demonstrates basic Docker image creation, container execution, port mapping, and web server deployment.
