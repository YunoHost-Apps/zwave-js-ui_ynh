<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Zwave-JS-UI für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Zwave-JS-UI mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Zwave-JS-UI schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Ausgelieferte Version:** 10.1.2~ynh1
## Dokumentation und Ressourcen

- Offizielle Website der App: <https://zwave-js.github.io/zwave-js-ui/#/>
- Offizielle Benutzerdokumentation: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Offizielle Verwaltungsdokumentation: <https://zwave-js.github.io/zwave-js-ui/#/>
- Upstream App Repository: <https://github.com/zwave-js/zwave-js-ui>
- YunoHost-Shop: <https://apps.yunohost.org/app/zwave-js-ui>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
oder
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
