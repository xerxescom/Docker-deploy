```sh
docker run -d \
--restart=always \
--name kg-postgres \
-p 5432:5432 \
-e POSTGRES_USER=root \
-e POSTGRES_PASSWORD=root123 \
-e PGDATA=/var/lib/postgresql/data/pgdata \
-v /opt/kg-postgresql/data:/var/lib/postgresql/data \
postgres
```

