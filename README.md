Dockerfile for EC-CUBE 3.x with docker-compose
====

## What's this

Development environment for [EC-CUBE 3.x](https://github.com/EC-CUBE/ec-cube).

## How to Build Image

* git clone

```zsh
git clone https://github.com/nanasess/docker-ec-cube3.git
```

## Example Usage

```zsh
cd docker-ec-cube3
docker-compose up -d
```

Let's Access in Browser
  * ex)```http://localhost:8080/admin```
    * ID: admin / PW: password
  * MailCatcher) ```http://localhost:1080/```

### Use for MySQL

```zsh
docker-compose --project-name mysql -f docker-compose.yml -f docker-compose.mysql.yml up -d
```

### Cleanup

```zsh
docker-compose stop
docker-compose rm
```

----
* This software is released under the MIT License, see LICENSE.txt.



