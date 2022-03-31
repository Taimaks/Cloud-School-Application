# SCA-Cloud-School-Application.
INSTRUCTIONS
============

Step 1:
-------
To build Docker image with Image tag use:
$ docker build -t <image_name>:<tag> </path/of/dockerfile>

Step 2:
-------
To run docker container in detach mode and with container's port(s) to the host:
$ docker run -d -p <host_port>:<container_port> <image_id>

Step 3:
-------
Stop docker container, take the image, login to dockerhub and push to dockerhub:
$ docker container stop <container_id>

$ docker commit dollysam/cloud-school-application <container_id>

$ docker login

$ docker push dollysam/cloud-school-application

Dockerhub link
---------------
https://hub.docker.com/repository/docker/dollysam/cloud-school-application

Webpage link:
3.95.63.63:8000
