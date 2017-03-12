[![CircleCI](https://circleci.com/gh/obytes/redis-browser-docker.svg?style=svg&circle-token=ba7381614eb8de5569f7e2723f35ada978edd079)](https://circleci.com/gh/obytes/redis-browser-docker)

# Redis-Browser Docker

A Docker image for browsing REDIS instance, the image uses [redis-browser](https://github.com/humante/redis-browser) to install service.


## Usage

```
docker pull obytes/redis-browser:latest
docker run obytes/redis-browser:latest --url redis://redis:6379
```
