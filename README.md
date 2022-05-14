# casa-docker
A docker container to run astronomy software CASA, based on Ubuntu 20.04

docker hub site:
https://hub.docker.com/repository/docker/djypku/casa

Using distrobox is recommended.see
https://github.com/89luca89/distrobox


Usage:
running

```
docker pull djypku/casa
distrobox create -i djypku/casa -n casa
distrobox enter casa
```
podman can also work for it,
