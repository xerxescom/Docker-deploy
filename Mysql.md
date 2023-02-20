```
docker pull mysql:8.0


docker run --name some-mysql \
-v /my/own/datadir:/var/lib/mysql \
-p 3306:3306 \
-e MYSQL_ROOT_PASSWORD=123456 -d \
mysql:8.0


docker exec -it xerxes-mysql bash

docker logs xerxes-mysql
```



