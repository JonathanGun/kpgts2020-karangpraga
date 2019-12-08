# Gamakta Karangpraga

## Setup and Install

(On ubuntu)

1. Install needed packages
   ```bash
   sudo apt update
   sudo apt install nginx mysql-server composer libssl-dev php-zip php-mbstring php-xml php-fpm php-mysql       php-common
   ```
1. Create user for your mysql, and create database named "gamakta"
1. `git clone https://github.com/yonasadiel/gamakta-karangpraga.git`
1. `cd gamakta-karangpraga`
1. `composer update`
1. `cp .env.example .env`
1. `php artisan key:generate`
1. `php artisan migrate`
