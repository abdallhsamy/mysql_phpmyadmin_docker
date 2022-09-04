# MySQL , PHPMyAdmin Docker-Compose

## Prerequisites
you must have [docker-compose](https://docs.docker.com/compose/install/) to run this script

and `docker-compose` requires  
- `Docker Engine`
- `Docker CLI`



## Installation

1 download the repose files
```bash
git clone git@github.com:abdallhsamy/mysql_phpmyadmin_docker.git
```
2 navigate to the downloaded folder
```bash
cd mysql_phpmyadmin_docker
```

2 pull and install the docker containers

```bash
docker-compose up -d


## Usage

```
1 run phpmyadmin using the [http://localhost:8081](http://localhost:8081)

2 use root credentials to access phpmyadmin:
- user : `root`
- password : `password`

or use the limited user to access `app_db` database:
- user : `user`
- password : `password`

![screenshot](screenshots/phpmyadmin.png "Login")
