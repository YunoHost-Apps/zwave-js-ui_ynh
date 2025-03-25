<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# Zwave-JS-UI per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Instal·la Zwave-JS-UI amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar Zwave-JS-UI de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Versió inclosa:** 10.1.1~ynh1
## Documentació i recursos

- Lloc web oficial de l'aplicació: <https://zwave-js.github.io/zwave-js-ui/#/>
- Documentació oficial per l'usuari: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Documentació oficial per l'administrador: <https://zwave-js.github.io/zwave-js-ui/#/>
- Repositori oficial del codi de l'aplicació: <https://github.com/zwave-js/zwave-js-ui>
- Botiga YunoHost: <https://apps.yunohost.org/app/zwave-js-ui>
- Reportar un error: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
o
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>
