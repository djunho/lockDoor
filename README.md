# LoockDoor


# Commands
```bash
docker build -t esp-docker:1.0 .
docker run --rm -it -v $PWD:/project --device=/dev/ttyUSB0 esp-docker:1.0 /bin/bash

make
make flash monitor
```
