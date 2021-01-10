# Alpine docker image with openjdk-15 and glibc

Just docker image for GitLab Runner  
GitLab: https://gitlab.com/persoff68-docker/alpine-openjdk-15-glibc  
Docker Hub: https://hub.docker.com/repository/docker/persoff68/alpine-openjdk-15-glibc  

Build:  
```
docker build -t persoff68/alpine-openjdk-15-glibc .
```

Run:  
```
docker run -d --name alpine-openjdk-15-glibc --restart always \
  persoff68/alpine-openjdk-15-glibc
```
