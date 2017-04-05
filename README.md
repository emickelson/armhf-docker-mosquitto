# armhf-docker-mosquitto
Docker file for Eclipse Mosquitto MQTT Broker on ARM

# [armhf-docker-mosquitto](https://hub.docker.com/r/ericmick/armhf-mosquitto/)


----------------------------------------
#### Description
* Distribution : [Alpine Linux](https://alpinelinux.org/)
* Architecture : armhf
* Base Image   : [armhf/alpine](https://hub.docker.com/r/armhf/alpine/)
* Appplication : [Mosquitto](https://github.com/ericontech/armhf-docker-mosquitto)
    - Eclipse Mosquitto MQTT broker on ARM architecture.



----------------------------------------
#### Run
* Simple Command
```sh
docker run -d -p 1883:1883 -p 9001:9001 ericmick/armhf-mosquitto:latest
docker kill -s SIGINT <container id>
```


#### Ports
| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| 1883               | -                                                |


#### Volumes
| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| 9001               | -                                                |


#### Environment Variables
| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |



----------------------------------------
[ericmick/armhf-mosquitto](https://hub.docker.com/r/ericmick/armhf-mosquitto/)
