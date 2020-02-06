# dnmp
doker compose for dnmp

## Usage

After git clone, change to root dir(location of docker-compose.yml), run:
```
docker-compose up -d
```
which will start php-fpm, nginx, redis, mysql.

If you just want to start partially, such as, redis, run:
```
docker-compose up -d redis
```
