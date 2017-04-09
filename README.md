# [alpine-armhf-mosquitto](https://hub.docker.com/r/ericmick/armhf-mosquitto/)
Docker file for Eclipse Mosquitto MQTT Broker on ARM

----------------------------------------
#### Description
* Distribution : [Alpine Linux](https://alpinelinux.org/)
* Architecture : armhf
* Base Image   : [armhf/alpine](https://hub.docker.com/r/armhf/alpine/)
* Application  : [Mosquitto](https://github.com/ericontech/alpine-armhf-mosquitto)
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
| 9001               | -                                                |


#### Volumes
| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables
| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |



----------------------------------------
[ericmick/armhf-mosquitto](https://hub.docker.com/r/ericmick/armhf-mosquitto/)
