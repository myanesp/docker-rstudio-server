# Docker-compose for RStudio Server (+ Traefik and Authelia)
This repository aims to unified services in order to deploy an instance of RStudio with docker.
Original image from RStudio is mantained by Dave Tang.

If you only want to deploy the server, please use the [docker-compose.yml](docker-compose.yml) file. If you want to deploy it and safely expose it to the Internet, please use the [docker-compose-traefik-authelia.yml](docker-compose-traefik-authelia.yml), which will deploy a full stack with Traefik as a reverse proxy and Authelia for login security.

(WIP)
