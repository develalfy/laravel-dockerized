The main purpose behind this repo is to create Laravel projects easily by 
just cloning this repo and putting a directory with name **app** in the root of it.

Installation
------------

* Clone/Download this repo
* `cd` what you've cloned
* `cp .env.example .env`
* Change configuration in the **.env** file
* `make up` or `docker-compose up -d`
* Put your **Laravel** files in directory and name that directory **app**
* `docker-compose exec fpm composer install` or `docker-compose exec fpm bash` to make more magick using bash

Notes
------------

PHP supported versions `7.4`, `8`