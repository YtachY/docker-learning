# docker-learning
https://roadmap.sh/projects/basic-dockerfile


- Build docker image from Dockerfile
```
docker build -t my-image:tag .
```
- Run the docker container
```
docker run -d -p 8080:8080 my-image
```

- Check log to verify
```
docker logs -f my-image
```