# WordPress Docker Setup

This repository contains a Docker Compose configuration to quickly set up a WordPress website with MariaDB and Redis.

## Getting Started

** You will need to have Traefik proxy
1. Clone this repository.
2. Customize the `.env` file with passwords and domain names.
3. Run `docker-compose up -d`.

## Services

- **wordpress**: WordPress with added PHP Redis extension.
- **mariadb**: MariaDB with added MySQLTuner.
- **redis**: Official Redis image for WordPress caching.
- **phpmyadmin**: phpMyAdmin for database management.

## Usage

Access your WordPress site via the defined domain. phpMyAdmin can be used for database management if enabled.

## Note

- Secure passwords are important.
- For local or development use.
- Adapt for production environments.