# PV Battery Guard Relay

An ESP32 Relay AC 30A is used in ESPHome to disconnect the AC power from the inverter depending on the required conditions.

## Prerequisites

Python wih `esphome` installed globally:

```shell
pip install esphome
```

## Check configuration and run build

```shell
esphome config ./pv-battery-guard.yaml
```

```shell
esphome run ./pv-battery-guard.yaml
```
