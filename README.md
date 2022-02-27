# Docker Demo

## Commands

```sh
# To enable port forwarding
docker run -p 5000:8080
#            local:container

# Find name of a Docker Container
docker ps

# Run interactive shell in a Docker Container
docker run -it container-name sh

# Run all your services using Docker Compose, from the instructions in `docker-compose.yml`
docker-compose up
```

## Notes

- each container should run a single process
- if your app needs multiple processes, you should use multiple containers
- to run multiple processes, you can use Docker Compose, which is basically a tool for running multiple containers at
  the same time

## Resources

- [Fireship: Learn Docker in 7 Easy Steps](https://www.youtube.com/watch?v=gAkwW2tuIqE)
- [Docker: Getting Started](https://docs.docker.com/get-started/)
- [How To Use docker exec to Run Commands in a Docker Container](https://www.digitalocean.com/community/tutorials/how-to-use-docker-exec-to-run-commands-in-a-docker-container)
- [Docker Hub: MySQL](https://hub.docker.com/_/mysql)
- [Docker Hub: Adminer](https://hub.docker.com/_/adminer)
