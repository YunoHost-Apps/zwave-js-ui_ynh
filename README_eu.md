<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zwave-JS-UI YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Instalatu Zwave-JS-UI YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zwave-JS-UI YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Paketatutako bertsioa:** 10.0.2~ynh1
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://zwave-js.github.io/zwave-js-ui/#/>
- Erabiltzaileen dokumentazio ofiziala: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Administratzaileen dokumentazio ofiziala: <https://zwave-js.github.io/zwave-js-ui/#/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/zwave-js/zwave-js-ui>
- YunoHost Denda: <https://apps.yunohost.org/app/zwave-js-ui>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
