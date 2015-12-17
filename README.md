# ObjectStyle ActiveMQ Docker Image
This is a ActiveMQ Docker image for ObjectStyle [site](http://www.objectstyle.com/). Built on top of [objectstyle/java8](https://hub.docker.com/r/objectstyle/java8/) image.

## Usage

`docker pull objectstyle/activemq`

Or, if you prefer to build it on your own:  
`docker build -t objectstyle/activemq .`

Run the image as daemon and bind it to port 8161:  
`docker run -d --name activemq --net=osllc -p $DOCKER_IP:8161:8161 objectstyle/activemq`