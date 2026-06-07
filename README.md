# Calculator App using Flask and Docker

A simple web-based calculator application built using Flask and containerized using Docker.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- User-friendly web interface
- Dockerized deployment

## Project Structure

```text
calculator-app/
├── app.py
├── Dockerfile
├── requirements.txt
├── templates/
│   └── index.html
└── README.md
```

## Prerequisites

- Docker installed
- Git installed

## Clone Repository

```bash
git clone https://github.com/PrajwalRayakar/calculator-app-docker.git
cd calculator-app-docker
```

## Build Docker Image

```bash
docker build -t calculator-app .
```

## Run Docker Container

```bash
docker run -d -p 5000:5000 --name calculator calculator-app
```

## Access Application

Open your browser:

```text
http://<EC2-Public-IP>:5000
```

Example:

```text
http://13.x.x.x:5000
```

## Stop Container

```bash
docker stop calculator
```

## Remove Container

```bash
docker rm calculator
```

## Docker Hub Image

```bash
docker pull <your-dockerhub-username>/calculator-app:latest
```

## Author

Prajwal Rayakar
