# Alpine InfluxDB

[![Docker Stars](https://img.shields.io/docker/stars/evild/alpine-influxdb.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-influxdb/)
[![Docker Pulls](https://img.shields.io/docker/pulls/evild/alpine-influxdb.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-influxdb/)
[![ImageLayers Size](https://img.shields.io/imagelayers/image-size/evild/alpine-influxdb/latest.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-influxdb/)

# Alpine InfluxDB

This image is based on [evild/alpine-base](https://hub.docker.com/r/evild/alpine-base/)

## Version
- `0.11`, `latest` [(Dockerfile)](https://github.com/Evild67/docker-alpine-influxdb/blob/master/0.11/Dockerfile)
- `0.10.3` [(Dockerfile)](https://github.com/Evild67/docker-alpine-influxdb/blob/master/0.10.3/Dockerfile)
- `0.9.6` [(Dockerfile)](https://github.com/Evild67/docker-alpine-influxdb/blob/master/0.9/Dockerfile)

## How to use this image

```
docker run -name alpine-influxdb -p 8083:8083 -p 8086:8086 evild/alpine-influxdb:0.11
```
