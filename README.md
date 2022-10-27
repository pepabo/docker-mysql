# docker-mysql

[![Docker Image CI](https://github.com/yano3/docker-mysql/actions/workflows/ci.yml/badge.svg)](https://github.com/yano3/docker-mysql/actions/workflows/ci.yml)

MySQL 5.7 Docker image with ARM64 architecture support. Based on [official MySQL image](https://github.com/docker-library/mysql).

## Differences from the official image

- With multi-platform (`linux/amd64`, `linux/arm64`) support
- Based on Ubuntu Bionic

## Tags

- [`5.7.40`](https://github.com/yano3/docker-mysql/blob/main/5.7/Dockerfile), [`5.7`](https://github.com/yano3/docker-mysql/blob/main/5.7/Dockerfile)
- [`5.7.39`](https://github.com/yano3/docker-mysql/blob/f91fd374ec28d433ac7f4cc11363c833bc0a249f/5.7/Dockerfile)

## How to use this image

You can use this image in the [same way as the official image](https://hub.docker.com/_/mysql) except for the differences described above.
