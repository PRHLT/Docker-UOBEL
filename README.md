# Docker-UOBEL

Base Ubuntu 16.04 image with preinstalled software in its required versions in order to compile
and execute correcty some of the document layout analysis developed software. 

## Software installed

- The following base software with specific versions : 

1. OpenCV 2.4.9 
2. Boost 1.58.0
3. Eigen3 3.2.92
4. Log4cxx 0.10.0

## Using the software image

In order to use the image (and launch a container)  you will need to first download (fastest) or build the container. 

* To download [vbosch/uobel](https://hub.docker.com/r/vbosch/uobel) or pull the current version of the hub image simply execute the following command:
	```
	sudo docker pull vbosch/uobel
	```
* To build the container clone this repository, go inside the downloaded repository and execute the following command: 
	```
	sudo docker build --rm  . -t uobel-docker
	```
