<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Zwave-JS-UI voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Zwave-JS-UI met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Zwave-JS-UI snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Geleverde versie:** 9.28.0~ynh1
## Documentatie en bronnen

- Officiele website van de app: <https://zwave-js.github.io/zwave-js-ui/#/>
- Officiele gebruikersdocumentatie: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Officiele beheerdersdocumentatie: <https://zwave-js.github.io/zwave-js-ui/#/>
- Upstream app codedepot: <https://github.com/zwave-js/zwave-js-ui>
- YunoHost-store: <https://apps.yunohost.org/app/zwave-js-ui>
- Meld een bug: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
of
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
