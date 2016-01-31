fork [https://github.com/docker-library/golang/blob/master/1.5/alpine/Dockerfile](https://github.com/docker-library/golang/blob/master/1.5/alpine/Dockerfile)

build Golang on Raspberry Pi with docker ([HypriotOS](http://blog.hypriot.com)).

```bash
# ARMv6 Raspberry Pi 1 model B+ (default)
$ docker build --build-arg GOARM=6 -t linguofeng/rpi-golang:ARMv6 .

# ARMv7 Raspberry Pi 2 model B
$ docker build --build-arg GOARM=7 -t linguofeng/rpi-golang:ARMv7 .
```
