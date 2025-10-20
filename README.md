# Cours Groupe Ali

This is a simple web application served via Docker using nginx.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone or download this repository.

2. Navigate to the project directory:
   ```
   cd cours-groupe-ali
   ```

3. Build and run the application using Docker Compose:
   ```
   docker-compose up --build
   ```

4. Open your browser and go to `http://localhost` to view the application.

5. To stop the application, press `Ctrl+C` in the terminal.

## Project Structure

- `index.html`: The main HTML page.
- `Dockerfile`: Defines the Docker image for the application.
- `docker-compose.yml`: Defines the services and how to run them.
- `README.md`: This file.

## Customization

You can modify the `index.html` file to change the content of the web page. The changes will be reflected when you rebuild the Docker image.
