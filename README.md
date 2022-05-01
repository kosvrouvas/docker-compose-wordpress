# WordPress with Docker Compose

This project includes:

With this project you can quickly run the following:

- [WordPress and WP CLI](https://hub.docker.com/_/wordpress/)
- [phpMyAdmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
- [MariaDB](https://hub.docker.com/_/mariadb)

## Requirements

In order to use this you need to have the latest versions of **Docker** and **Docker Compose** installed on your machine.

Clone this repository or copy the files from this repository into a new folder. In the **docker-compose.yml** file you may change the IP address (in case you run multiple containers) or the database from MySQL to MariaDB.

## Installation

Open a terminal and `cd` to the folder in which `docker-compose.yml` is saved and run:

```
docker-compose up
```
The containers are now built and running. You should be able to access the WordPress installation with the configured IP in the browser address. By default it is `localhost:8000`.
