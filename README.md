# my esphome configs

## Overview

The configurations are modular. Each device will have a single yaml file, this file will use a device specific file from the templatefiles directory.

The device specific file will then import the common settings from either

- [common.yaml](templatefiles/common.yaml) (THIS USES DHCP)
- [common_static.yaml](templatefiles/common_static.yaml) (THIS USES STATIC IP)

The common files will pull the secrets from templatefiles/secrets.yaml

## Devices

- NodeMCU

  [Configuration file: templatefiles\roomsensor.yaml](templatefiles/roomsensor.yaml)

- esp32
  
  [Configuration file: templatefiles\roomsensor_esp32.yaml](templatefiles/roomsensor_esp32.yaml)

- espcam32

  [Configuration file: templatefiles\aithinker_esp32cam.yaml](templatefiles/aithinker_esp32cam.yaml)

- SonOff POW R1

  [Configuration file: templatefiles\sonoffpowr1.yaml](templatefiles/sonoffpowr1.yaml)

- SonOff POW R2

  [Configuration file: templatefiles\sonoffpowr2.yaml](templatefiles/sonoffpowr2.yaml)

- Blackboard-T5

  [Configuration file: templatefiles\blackboardt5.yaml](templatefiles/blackboardt5.yaml)
