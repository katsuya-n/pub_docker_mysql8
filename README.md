# pub_docker_mysql8
MySQL起動

```
$ docker image build -t test-mysql8 .
$ docker container run -d --name test-mysql8 -e MYSQL_ROOT_PASSWORD=password -p 3306:3306 test-mysql8
$ mysql -uroot -h 127.0.0.1 -ppassword -P 3306
```
