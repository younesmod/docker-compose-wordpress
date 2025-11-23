![Docker Image](https://img.shields.io/badge/GHCR-WordPress-blue?logo=docker)
[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/younesmod/docker-compose-wordpress/blob/main/LICENSE)
[![Scan Docker Image](https://github.com/younesmod/docker-compose-wordpress/actions/workflows/scan.yml/badge.svg?branch=main)](https://github.com/younesmod/docker-compose-wordpress/actions/workflows/scan.yml)
[![Build and Push Docker Images](https://github.com/younesmod/docker-compose-wordpress/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/younesmod/docker-compose-wordpress/actions/workflows/docker-publish.yml)
# 🐳 WordPress + MySQL with Docker Compose

A clean, production-style setup for running WordPress and MySQL using Docker Compose.

## 🚀 Features
- Two-tier containerized stack (WordPress + MySQL)
- Persistent data with Docker volumes
- Secure configuration using environment variables
- Healthcheck for database service
- Auto-restart and network isolation

## 🧩 Setup
1. **Clone the repo**
    ```bash
    git clone https://github.com/younesmod/docker-compose-wordpress.git
    cd docker-compose-wordpress
    ```
2. **Create .envfile**
    ```bash
    cp .env.example .env
    # edit your credentials inside .env
    ```

3. **Run the stack**
    ```bash
    docker-compose up -d
    ```
4. **Access the site**

-   WordPress: http://localhost:8080

## 🧹 Cleanup
```bash
docker-compose down -v
```
