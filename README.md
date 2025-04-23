# Full Stack Application: DevOps Assistant & Code Explainer
This project consists of a full-stack web application built with FastAPI (Python) for the backend and Next.js (React) for the frontend. It includes various services for DevOps assistance, code explanation, and interview bot functionality. The application is dockerized using Docker Compose, allowing for easy deployment and testing in a containerized environment.



## Tech Stack
- Frontend: React, Next.js

- Backend: FastAPI, Python

- Docker: Docker Compose for managing containers

- API Integration: OpenAI API for generating responses

#Prerequisites
Before you start, ensure you have the following installed:

- Docker

- Docker Compose

- Node.js

- Python 3.x


# Getting Started
## 1. Clone the Repository
Clone the repository to your local machine:
```
git clone https://github.com/yourusername/devops-assistant.git
cd devops-assistant
```

## Setup Environment Variables
Before running the application, make sure to set up environment variables.

## Backend
In the backend/ directory, create a .env file and add your OpenAI API Key:

```
OPENAI_API_KEY=your-openai-api-key-here
```

 ## Docker Setup

 ```
docker-compose up --build
```



