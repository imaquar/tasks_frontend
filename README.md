# Frontend Task Planner Application by Yandex Practicum

This is the frontend part of a task planning application developed as part of the Yandex Practicum program.

---

## Getting Started

Follow these steps to run the project using Docker:

### 1. Prerequisites

Ensure Docker is installed on your system. You can download it from [https://www.docker.com/](https://www.docker.com/).

### 2. Clone the Repository

Download or clone the repository to your local machine:

```bash
git clone https://github.com/imaquar/tasks_frontend.git
cd tasks_frontend
```

---

## Setup Instructions

### 1. Build the Docker Image

In the root directory of the project, run:

```bash
docker build -t name_of_project .
```

This command builds the Docker image for the frontend.

### 2. Run the Docker Container

To run the container, execute:

```bash
docker run -p 8080:8080 name_of_project
```

The application will now be accessible at:

```bash
http://localhost:8080
```

### 3. Manage the Container

To list all running containers and get the container ID, run:

```bash
docker ps
```

To stop the running container, use the following command:

```bash
docker stop <id_of_container>
```

Replace <id_of_container> with the actual container ID you obtained in the previous step.
