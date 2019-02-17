Docker Duck DNS Updater
=======================

Runs a Docker container using Docker Compose to update Duck DNS.

Build with:
```php
docker build -t duckdns .
```

Edit docker-compose.yml file to change:
```php
    environment:
      - DOMAINS=xxx
      - TOKEN=xxx
```

Run with:
```php
docker-compose up
```

Thanks to the main script from : https://github.com/theonemule/docker-dynamic-dns