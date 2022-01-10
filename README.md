# k8s-bastion
Bastion host inside Kubernetes using Ubuntu + SSH

## How to build & push

You need to run:

```
docker buildx build --platform linux/amd64,linux/arm64 --push -t [tag] .
```

## Credentials for the ssh

Username and password is `bastion` but you can set up whatever you want or even an ssh key for authentication.

## Available on Docker

It's already built in into my Dockerhub account: https://hub.docker.com/repository/docker/mhonorio/bastion
