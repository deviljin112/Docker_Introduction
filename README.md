# Docker Introduction

## What is docker

- Docker is an open source platform.
- It helps and enables us to seperate applications from the infrastructure.
- It allows us to deliver software faster.
- Docker is writen in GO language.

## Why Docker

- Largest Conglomorates are using or adapting Docker.
  - Ebay
  - Netflix
  - Sky
  - Many more
- Docker adoption is anticipated by 50% by the end of 2020
- Multiplatform

## Difference vs VirtualMachines

- Docker is light-weight and user friendly
- Docker shares the resources of the OS vs using a seperated OS
- Docker engine connects the container with OS and only use the resources required
- VM works with Hypervisor to connect guest OS/VM with host OS/server

## Demand and future of Docker

## Docker API

Syntax and Commands:

```bash
docker pull <image_name>
docker run <image_name>
docker build -t <image_name>
docker commit <image_name>/<container_id>
docker start <container_id>
docker stop <container_id>/<name>
docker rm <container_id>/<name>
docker ps
docker ps -a
```

### Logging into a container

```bash
docker exec -it <name>/<id>
```
