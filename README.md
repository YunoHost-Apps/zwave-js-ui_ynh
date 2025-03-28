<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Zwave-JS-UI for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Working status](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Maintenance status](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Install Zwave-JS-UI with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Zwave-JS-UI quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Shipped version:** 10.1.2~ynh1
## Documentation and resources

- Official app website: <https://zwave-js.github.io/zwave-js-ui/#/>
- Official user documentation: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Official admin documentation: <https://zwave-js.github.io/zwave-js-ui/#/>
- Upstream app code repository: <https://github.com/zwave-js/zwave-js-ui>
- YunoHost Store: <https://apps.yunohost.org/app/zwave-js-ui>
- Report a bug: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
or
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
