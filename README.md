# Alpine docker image with openjdk-13 and glibc

Just docker image for GitLab Runner  
GitLab: https://gitlab.com/persoff68-docker/alpine-openjdk-13-glibc  
Docker Hub: https://hub.docker.com/repository/docker/persoff68/alpine-openjdk-13-glibc  

Build:  
```
docker build -t persoff68/alpine-openjdk-13-glibc .
```

Run:  
```
docker run -d --name alpine-openjdk-13-glibc --restart always \
  persoff68/alpine-openjdk-13-glibc
```
