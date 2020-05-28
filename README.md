# CODEWARS

## Install
Install submodules 

`git submodule update --init`

Add to file /etc/hosts on system next host:

```
127.0.0.1   cm.codewars.ua 
127.0.0.1   adminer.codewars.ua 
```

Build images

`docker-compose build`

## Run project

`docker-compose up`

`docker-compose run --rm backend npx sequelize-cli db:migrate`