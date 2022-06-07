# rails-ci-aws
Creating a CI pipeline for rails docker project using AWS services

# Project starting steps

```
$ docker-compose build
$ docker-compose up
```

# Initial db setup

```
$ docker exec -it rails sh
$ rake db:create
$ rake db:migrate
```

# Enter into rails container

```
$ docker exec -it rails sh
```

# Enter into MySQL container

```
$ docker exec -it db sh
$ mysql -u root -p
$ use mysql;
```