# docker-host
Docker image to forward all traffic to the docker host

[![Docker Stars](https://img.shields.io/docker/stars/qoomon/docker-host.svg)](https://hub.docker.com/r/qoomon/docker-host/)

# Run
```docker run --cap-add=NET_ADMIN --cap-add=NET_RAW qoomon/docker-host```