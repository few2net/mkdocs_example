This part of the project documentation focuses on a

```bash
docker run --name mariadb --env-file /home/aom/visset_ws/my_env_file -v mariadb:/var/lib/mysql -d -p 3306:3306 --rm mariadb:latest
```

```bash
docker run --name snipeit --env-file /home/aom/visset_ws/my_env_file -v snipeit:/var/lib/snipeit -p 8118:80 -d --rm snipe/snipe-it:latest
```