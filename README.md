### start container

    docker-compose up -d

### web

    http://localhost:8888/

### exec wp 

    docker-compose run -rm wordpress wp help

### note

Local `src` directory is mapped `/var/www/html` on a container.

WordPress source will be copied to `/var/www/html` when a container start everytime.

