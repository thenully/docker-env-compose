# docker-env-compose
Docker compose for docker-env

### Start
Execute for setting up some particular services

```
docker-compose up -d --no-recreate <service>
```

### Remove
```
docker-compose stop <service> && docker-compose rm --force <service>
```

### Update images
```
docker-compose pull <service>
```

### Statefull services
For saving a state of a service you can use the stop command

```
docker-compose stop <service>
```

### Useful links
1. https://docs.docker.com/compose/
2. https://github.com/docker/compose
3. https://github.com/sdurrheimer/docker-compose-zsh-completion
4. http://stackoverflow.com/a/32023104/1553664
5. https://github.com/chadoe/docker-cleanup-volumes – remove unused images
6. https://github.com/brogersyh/Dockerfiles-for-windows
