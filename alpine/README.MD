# linux container with alpine version

## Steps
1. write compose file
2. check .env file to setup environment variables
3. execute docker and docker-compose command
4. connect to container use command line or GUI tool

## Scripts

``` bash
docker-compose up -d  

# access  docker container via terminal
docker exec -it alpine_service_dev_local sh

```

## References
1 [docker doc](https://hub.docker.com/_/alpine?tab=description)
