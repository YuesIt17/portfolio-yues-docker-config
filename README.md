# 🐳Docker Config Repository

This repository contains Docker configurations and orchestration, which consists of a frontend built with **NestJS** and a backend built with **Next.js**. It uses Docker Compose to define and run multi-container Docker applications.

## Overview

This repository serves as the central location for managing the Docker containers for both the frontend and backend of the application. It contains a `docker-compose.yml` file that defines how to build and run these services alongside a PostgreSQL database.

## Configuration

### Docker Compose File

The `docker-compose.yml` defines three services:

1. **Database**: A PostgreSQL database for persistent storage.
2. **Backend**: The NestJS application.
3. **Frontend**: The Next.js application.

You can customize the configurations in the `docker-compose.yml` file to suit your needs, such as changing the ports or database credentials.

## Usage

To run the application locally using Docker Compose, follow these steps:

- to create images for:

  - [frontend](https://github.com/YuesIt17/yuit-docs-nextjs-docker/blob/main/README.md#settings-of-docker-image-for-frontend)
  - [backend](https://github.com/YuesIt17/yuit-docs-nestjs-docker/blob/main/README.md#settings-of-docker-image-for-backend)
  - [database](https://github.com/YuesIt17/yuit-docs-nestjs-docker/blob/main/README.md#settings-of-docker-for-db)

- to run the containers via: `docker-compose up -d`
- to stop and remove the containers via: `docker-compose down`
