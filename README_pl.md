<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Zwave-JS-UI dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Status działania](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Zainstaluj Zwave-JS-UI z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Zwave-JS-UI na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Dostarczona wersja:** 9.33.1~ynh1
## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://zwave-js.github.io/zwave-js-ui/#/>
- Oficjalna dokumentacja: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Oficjalna dokumentacja dla administratora: <https://zwave-js.github.io/zwave-js-ui/#/>
- Repozytorium z kodem źródłowym: <https://github.com/zwave-js/zwave-js-ui>
- Sklep YunoHost: <https://apps.yunohost.org/app/zwave-js-ui>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
lub
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
