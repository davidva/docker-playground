# Docker Playground

```
docker-machine create --driver virtualbox default
docker-machine ls
docker-machine stop default
docker-machine start default

eval $(docker-machine env default)
docker run --rm busybox echo hello world
docker run -it --rm busybox:latest
docker run -d -p 8000:80 nginx
docker-machine ip default
docker ps
```
