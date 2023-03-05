# Sony KD-49XH8505 to MQTT

Sony Bravia Android TV integration via MQTT in [Homie Convection](https://homieiot.github.io/)

Tested on **Sony KD-49XH8505**

```yaml
version: '3.2'
services:
  sony-bravia-to-mqtt:
    container_name: sony
    image: rzarajczyk/sony-bravia-to-mqtt:latest
    volumes:
      - ./config/sony-bravia-to-mqtt.yaml:/app/config.yaml
    restart: unless-stopped
```

## Configuration

TODO