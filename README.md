# docker-compose-guacamole

run

```bash
docker run --rm guacamole/guacamole /opt/guacamole/bin/initdb.sh --postgres > init/initdb.sql
docker-compose -p guac up -d
```

Then go to `http://DOCKER_HOST:8080/guacamole/`

Log in as user: `guacadmin` and password: `guacadmin`.
