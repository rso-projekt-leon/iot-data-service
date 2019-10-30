## Literatura
- [Dockerizing Flask with Postgres, Gunicorn, and Nginx](https://testdriven.io/blog/dockerizing-flask-with-postgres-gunicorn-and-nginx/)

## Docker compose dev
- docker-compose build
- docker-compose up -d
- docker-compose down
- docker-compose logs -f

## Docker-compose prod
- docker-compose -f docker-compose.prod.yml up -d --build
- docker-compose -f docker-compose.prod.yml down -v
- docker-compose -f docker-compose.prod.yml exec app python manage.py create_db
