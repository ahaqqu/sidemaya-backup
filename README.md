# sidemaya
Sistem Informasi Desa Manud Jaya

## Setup

Steps:
- Install Docker Desktop
- Install Github Desktop
- Checkout this project
- Copy `.env` to `laradock` folder
- Start cmd at checkout location
  - `cd laradock/`
  - `docker-compose up -d nginx mysql`
  - `docker-compose exec --user=laradock workspace bash`


docker-compose exec nginx nginx -t
docker-compose exec nginx nginx -s reload