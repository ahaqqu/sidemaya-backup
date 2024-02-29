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
    - `composer create-project laravel/laravel my-cool-app "5.2.*"`



docker exec Nginx nginx -t
docker exec Nginx nginx -s reload