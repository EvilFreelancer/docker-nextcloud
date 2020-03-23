# Docker composition of Nextcloud

Composition of containers for using Nextcloud

## How to use

Just clone this repo then go to folder with sources

    git clone https://github.com/EvilFreelancer/docker-nextcloud.git
    cd docker-nextcloud

Copy dist configs and fix your parameters if need

    cp -v docker-compose.yml.dist docker-compose.yml
    cp -v configs/nginx/conf.d/default.conf.dist configs/nginx/conf.d/default.conf

Start composition of containers

    docker-compose up -d

Go to http://localhost and install the system.

## Links

* https://nextcloud.com/
* https://github.com/nextcloud
* https://hub.docker.com/_/nextcloud/
