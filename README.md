# Symfony 5 + PHP-FPM + MySQL 8 + nginx

Run a containerized symfony application

```
git clone git@gitlab.com:kylewhat/symfony5.git

cd docker

docker-compose up
```

### PHP (PHP-FPM)

Composer is included

```
docker-compose run php-fpm composer 
```

To run fixtures

```
docker-compose run php-fpm bin/console doctrine:fixtures:load
```
