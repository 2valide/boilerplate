# Docker PHP - Quick Start

This project provides a simple setup to run a PHP server using Docker.

## Prerequisites
- [Docker](https://www.docker.com/) installed on your machine
- [Docker Compose](https://docs.docker.com/compose/) installed

## Installation and Startup
1. Open a terminal in the `php/` directory.
2. Run the following command to start the PHP server:
   ```zsh
   docker-compose up -d
   ```
3. The PHP server will be accessible on the port defined in the `docker-compose.yml` file (default: 80).

## Usage
- Go to `http://localhost` in your browser to see the result.

## Stopping and Cleanup
To stop the containers:
```zsh
docker-compose down
```
To remove volumes and associated images:
```zsh
docker-compose down --volumes --rmi all
```

## Project Structure
- `Dockerfile`: PHP image configuration
- `docker-compose.yml`: Docker services orchestration
- `index.php`: Example PHP file
- `start.md`: Documentation and instructions (this file)

---
Feel free to adapt the configuration to your needs!
