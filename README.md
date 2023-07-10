# NGINX and PHP-FPM 8.1
Nginx and php-fpm container stack using docker-compose

## HOW TO USE
Simply use docker-compose command to create this docker container stack.

```
docker-compose -f nginx-compose.yml up -d
```

* It will exposing port `8082` from your host to port `80` inside nginx container. 
* Put your php project to `www` directory.
* To add more configuration you can change nginx `default.conf` and php.ini inside `config` directory.
* Open `localhost:8082` to check if this container is working.