
### Custom Docker Node, Nginx Image

#### Usage

```
docker pull sydrawat/nginx-website
```

#### RUN

```
 docker container run -it -p 8082:80 sydrawat/nginx-website
```
> You can use any port number instead of ```8082```, but the port number ```80``` is default for nginx.

For a detailed explanation, you can checkout the image repository [here](https://hub.docker.com/r/sydrawat/nginx-website) at [Docker Hub](https://hub.docker.com/).