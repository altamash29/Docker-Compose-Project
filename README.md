# Docker Compose Assignment

This project provides a Docker Compose configuration file for running a WordPress website with a MySQL database. The Docker Compose file sets up a WordPress container and a MySQL container for the database.

## Prerequisites

Before running this project, you need to have Docker and Docker Compose installed on your system.

## Usage

To run this project, simply clone the repository and run the following command:

docker-compose up -d

This will start the WordPress and MySQL containers in detached mode, allowing them to run in the background.

To stop the containers, run the following command:

docker-compose down

## Configuration

The Docker Compose file includes configuration options for the WordPress container, such as the WordPress version and database credentials. You can modify these options by editing the docker-compose.yml file.
