Esphome MQTT TLS minimal sample
===============================

Installation
------------

## Setup

- Choose platform and board in `secrets.yaml`
  (see https://esphome.io/components/esphome.html#configuration-variables)
- Copy `secrets.yaml.sample` to `secrets.yaml`
  
## Compile and run
```shell
poetry install
poetry run esphome run --device /dev/ttyUSB0 mqtt-tls-sample.yaml 
```


