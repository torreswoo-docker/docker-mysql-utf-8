# mysql-utf-8
- Docker Container 
- Official MySQL Docker Container : https://hub.docker.com/_/mysql/
- MySQL | 5.7
- add my.cnf
  - UTF-8

# running
```
$ docker build -t mysql-utf-8:latest .
$ docker run --name abt-web-mysql-utf-8 mysql-utf-8:latest
```
