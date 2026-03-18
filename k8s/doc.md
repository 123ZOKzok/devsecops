## Container Orchestration

Its automated management of containerized applications across multiple hosts, handling deployment, scaling, networking and availability.

## Docker

Containerization platform that packages applications with their dependencies into lightweight, portable containers.

### Basic Docker Commannds
 
 #### Build image
 ```bash
 docker build  -t myapp .
 ```
 #### Run container
 ```bash
 docker run -p 8080:80 myapp 
 ```
 #### List containers
 ```bash
 docker ps 
 ```