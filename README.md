# NGINX and PHP-FPM 8.1
Nginx and php-fpm container stack using docker-compose

## HOW TO USE
Simply use docker-compose command to create this docker container stack.

```
docker-compose up -d
```

* It will exposing port 8082 from host to port 80 inside nginx container.
* put your php project to `www` directory.
* to add more configuration you can change nginx default.conf and php.ini inside `config` directory.