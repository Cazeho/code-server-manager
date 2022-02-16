# code-server-manager

code-server for multi users

- sqldatabase (insert/preview)
- secure manager app
- easy to configure

## Policy

1 container= 1 user


## Install

```

bash init.sh

edit docker-compose and nginx.conf (need to edit for each user)

docker-compose up -d

pip -r requirements.txt

python3 insert.py


```
