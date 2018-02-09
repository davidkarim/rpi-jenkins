## rpi-jenkins-docker

Jenkins for Docker on Raspberry Pi

On your Raspberry Pi, follow these steps:
```
docker build -t rpi-jenkins .
docker run -td -p 8100:8080 rpi-jenkins
```
Assuming the hostname of the Pi is raspberrypi, from any machine on the network, go to the following URL:
```
http://raspberrypi.local:8100
```
