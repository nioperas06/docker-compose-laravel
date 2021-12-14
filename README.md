# docker-compose-laravel
> A simplified Docker Compose workflow for local Laravel development: PHP, NGINX, POSTGRESQL, COMPOSER, NPM, REDIS, MAILHOG

## Usage
Spin up the containers by running:

```
docker-compose up --build
```

Other commands:
- `docker-compose run --rm composer update`
- `docker-compose run --rm npm run dev`
- `docker-compose run --rm artisan migrate`
