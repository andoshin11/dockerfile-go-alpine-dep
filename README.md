# Docker Hub Link
https://hub.docker.com/r/andoshin11/go-alpine-dep/

# What is this?
Docker Image for Golang Developers.
Since dep package manager is not installed on official Docker image, this may help you run app on cloud easily.

# What's included?
This Docker Image includes:
- golang 1.10.2
- git
- dep

# How to Use
You can either clone or pull this image. Choose the way suits your need the most.

1. Clone this image and build the image by yourself

```
$ git clone https://github.com/andoshin11/dockerfile-go-alpine-dep.git
$ docker build -t name:tag .
```

2. Pull from Docker Hub <Recommended>
```
$ docker pull andoshin11/go-alpine-dep
```
