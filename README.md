# WebOne HTTP 1.X Proxy on Docker

This is the work in progress version of Docker image with **[WebOne](https://github.com/atauenis/webone) Proxy Server** by **Alexander Tauenis** 👍 on board.

Please refer to the original 🔥 [Wiki](https://github.com/atauenis/webone/wiki) page before to change configuration files.

## **+ Setup**

- You can build an image yourself:

> `git clone ...`
> 
> `cd docker-webone`
> 
> `docker build -t IMAGE_NAME .`
> 
> `docker run -d -p 8080:8080 -v /your/local/webone.config:/home/webone --name CONTAINER_NAME IMAGE_NAME`

- Or download it from **[DockerHub](https://hub.docker.com/repository/docker/u306060/webone)**.


