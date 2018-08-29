[![Version](https://img.shields.io/badge/version-0.0.1-green.svg?style=for-the-badge)](#) [![mantained](https://img.shields.io/maintenance/yes/2018.svg?style=for-the-badge)](#)

[![maintainer](https://img.shields.io/badge/maintainer-Peter%20Skopa%20%40toast-blue.svg?style=for-the-badge)](#)

# sensor.geoip
A sensor that returns most info about your ip [Home Assistant](https://www.home-assistant.io/) 

To get started put `/custom_components/sensor/geoip.py` here:
`<config directory>/custom_components/sensor/geoip.py`

**Example configuration.yaml:**

```yaml
sensor:
  platform: geoip
```
Due to how `custom_componentes` are loaded, it is normal to see a `ModuleNotFoundError` error on first boot after adding this, to resolve it, restart Home-Assistant.
