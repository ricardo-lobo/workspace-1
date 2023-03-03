# workspace-1

This is a simple development environment using MariaDB, SingleStore, and Redis.

## Prerequisites (recommended)

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [SingleStore License](https://www.singlestore.com/try-singlestore/)
- [HeidiSQL](https://www.heidisql.com/download.php) (optional for windows)
- [TablePlus](https://tableplus.com/download) (optional for mac)

## Getting Started

1. Install [Docker Desktop](https://www.docker.com/products/docker-desktop)
2. For Windows, when prompted, enable WSL 2
3. Register for a [SingleStore License](https://www.singlestore.com/try-singlestore/)
4. Clone this repository
5. Create a `.env` file in the root of the repository (see `.env.example`)
6. Run `docker-compose up -d` to start the containers

## Connecting to MariaDB

1. Open HeidiSQL or TablePlus
2. Create a new connection
3. Set the connection type to MariaDB
4. Set the host to `localhost`
5. Set the port to `3306` or the port configured in the .env file
6. Set the username to `root`
7. Set the password to the password configured in the .env file

## Connecting to SingleStore

1. Open HeidiSQL or TablePlus
2. Create a new connection
3. Set the connection type to MySQL
4. Set the host to `localhost`
5. Set the port to `3307` or the port configured in the .env file
6. Set the username to `root`
7. Set the password to the password configured in the .env file
