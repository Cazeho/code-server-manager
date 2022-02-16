# code-server-manager (for docker)

code-server for multi users

- sqldatabase (insert/preview)
- secure manager app
- easy to configure


environement: on docker and docker-compose

## distro

ubuntu

Debian

## Policy

1 container = 1 user


## Install

```

bash init.sh

edit docker-compose and nginx.conf (need to edit for each new user)

docker-compose up -d

pip -r requirements.txt

python3 insert.py


```
