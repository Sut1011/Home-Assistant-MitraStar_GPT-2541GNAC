# MitraStar_GPT-2541GNAC Fiber Router device tracker for Home Assistant
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://hacs.xyz/)

The `MitraStar_GPT-2541GNAC` platform for `device_tracker` integration allows you to detect presence by looking at connection devices to a wireless router.


## Installation
Recommended: use [HACS](https://hacs.xyz/).

Manual: copy `custom_components/MitraStar_GPT-2541GNAC` folder into your `custom_components`.

## Configuration
```yaml
# Example configuration.yaml entry
device_tracker:
  - platform: MitraStar_GPT-2541GNAC
    host: 192.168.1.1
    username: 1234
    password: router_password
```

If your device is not in the list, you can still give it a try and let me know if it works or not, I'll update the documentation.

*Disclaimer*: I cannot add support for devices I don't own, but external contributions are definitely welcome. Feel free to open an issue on Github if you want to help.

## Documentation

