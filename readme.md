# WordPress Docker Compose Setup

This project sets up WordPress with MySQL and phpMyAdmin using Docker Compose.

## Prerequisites

- Docker
- Docker Compose

## Setup

1. Clone this repository
2. Create a `.env` file in the project root

## Usage

To start the services:
```bash
docker compose up -d
```

Access:
- WordPress: http://localhost:8090
- phpMyAdmin: http://localhost:8081

To stop the services:
```bash
docker compose down
```

## Services

- WordPress
- MySQL
- phpMyAdmin

## Environment Variables

- `MYSQL_PASSWORD`
- `MYSQL_ROOT_PASSWORD`
- `MYSQL_DB_NAME`
- `MYSQL_USER`

## Notes

- Ensure to keep your `.env` file secure and never commit it to version control.
- For production use, consider using a more secure secret management solution.