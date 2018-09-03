1. clone this repository
2. go to tomcat-basic directory
3. run following commands 

docker build -t <tag-name> <Dockerfile-path-till-parent-directory>

docker run -p <host-port>:<container-port> <tag-name>