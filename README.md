# Project: Visitor Counter API

## Overview
You are provided with a Python Flask application that interacts with a Redis database to track visitor counts. Your goal is to containerize the API and use **Docker Compose** to manage the communication and lifecycle of both services.

---

## Requirements

### Phase 1: Dockerizing the Flask API
Create a `Dockerfile` for the provided `main.py`. The python version used is 3.7

### Phase 2: Orchestration with Docker Compose
Create a `docker-compose.yml` file in the root directory to define the following architecture:

1.  **Service: `web`**
    * Ensure it **depends on** the redis service.
2.  **Service: `redis`**

---

## How to Submit Your Work

1.  **Fork this Repository**
2.  **Clone Your Fork**
3.  **Develop a solution**
4.  **Commit & Push**
5.  **Submit a Pull Request (PR)**
