# Laravel Application that is deployed through docker-compose
## Steps to follow this lab
### 1. Install docker
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04
### 2. install docker-compose
https://www.digitalocean.com/community/tutorials/how-to-install-and-set-up-laravel-with-docker-compose-on-ubuntu-20-04
### 3. clone repo
```bash
$ git clone https://github.com/sobankhan12/laravel-docker-compose.git
```
### 4. run these commands
 ```bash
$ cd laravel-docker-compose
$ docker-compose build app
$ docker-compose up -d 
$ docker-compose exec app php artisan key:generate
```
# Note
if you want to change configuration like **password, db_host env variable** then open **.env** file 
