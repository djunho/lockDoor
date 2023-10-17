# lockDoor

Using ESPHOME

# Commands

```
docker pull ghcr.io/esphome/esphome
docker run --rm -v "${PWD}":/config -it ghcr.io/esphome/esphome wizard ./lock.yaml
docker run --rm --privileged -v "${PWD}":/config --device=/dev/ttyUSB0 -it ghcr.io/esphome/esphome run ./lock.yaml

# To configure it on web interface
docker run --rm --net=host -v "$PWD":/config -it ghcr.io/esphome/esphome
```
