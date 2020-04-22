# Dockerized Odoo with HTTPS

## Image

Odoo:13.0
Postgres:11.7

## Database Configuration

Tweak the environment variables in `docker-compose.yml`
- Match the environment variables between services web (HOST, USER, PASSWORD) and db (POSTGRES_DB, POSTGRES_PASSWORD, POSTGRES_USER)

## Troubleshooting

`docker exec -ti odoo`
