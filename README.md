# my esphome configs

## Overview

The configurations are modular. Each device will have a single yaml file, this file will use a device specific file from the templatefiles directory.

The device specific file will then import the common settings from either

- [common.yaml](templatefiles/common.yaml) (THIS USES DHCP)
- [common_static.yaml](templatefiles/common_static.yaml) (THIS USES STATIC IP)

The common files will pull the secrets from templatefiles/secrets.yaml

## Devices

- NodeMCU

  [Configuration file: templatesfiles\roomsensor.yaml](templatesfiles/roomsensor.yaml)

- esp32
  
  [Configuration file: templatesfiles\roomsensor_esp32.yaml](templatesfiles/roomsensor_esp32.yaml)

- espcam32

  [Configuration file: templatesfiles\aithinker_esp32cam.yaml](templatesfiles/aithinker_esp32cam.yaml)

- SonOff POW R1

  [Configuration file: templatesfiles\sonoffpowr1.yaml](templatesfiles/sonoffpowr1.yaml)

- SonOff POW R2

  [Configuration file: templatesfiles\sonoffpowr2.yaml](templatesfiles/sonoffpowr2.yaml)

- Blackboard-T5

  [Configuration file: templatesfiles\blackboardt5.yaml](templatesfiles/blackboardt5.yaml)
