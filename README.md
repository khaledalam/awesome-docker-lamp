![Docker Pulls](https://img.shields.io/docker/pulls/khaledalam/awesome-docker-lamp)
![Docker Stars](https://img.shields.io/docker/stars/khaledalam/awesome-docker-lamp)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/khaledalam/awesome-docker-lamp)

# Awesome Docker Lamp
A Docker image with simple script to build LAMP stack apps (Ubuntu, Apache, PHP and MySql) using single docker image.

<img src="https://github.com/khaledalam/awesome-docker-lamp/blob/master/examples/logos/2.png?raw=true" width="400"><img src="https://github.com/khaledalam/awesome-docker-lamp/blob/master/examples/logos/1.png?raw=true" width="400">

## Features (NEW)
- `nano` editor added!
- new tag with `node` and `npm`!


## Tags
- without node: (~845MB) ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/khaledalam/awesome-docker-lamp/latest-without-node)<br>`docker pull khaledalam/awesome-docker-lamp:latest-without-node`
- with node: (~920MB) ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/khaledalam/awesome-docker-lamp/latest-with-node)<br>`docker pull khaledalam/awesome-docker-lamp:latest-with-node`


## Run
- `git clone git@github.com:khaledalam/awesome-docker-lamp.git`
- `cd awesome-docker-lamp`

PHP:
- `bash build_php.sh`

NODE:
- `bash build_node.sh`

go to url: http://your_host_ip:8000 <br>
ex. http://127.0.0.1:8000 <br>
ex. http://localhost:8000 <br>

## FAQ
- Got error `.. bind: address already in use ..`
    ```
    Make sure to use ports which are open and not in use on your host machine.
    
    PORT_HOST=8001
    PORT_HOST_SQL=3306

    ex. `8001` and `3306` 
    ```



## Inspiration
This image was originally based on [mattrayner/docker-lamp](https://github.com/mattrayner/docker-lamp), with a few changes to make building much eaiser.
