<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Zwave-JS-UI untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Status kerja](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Pasang Zwave-JS-UI dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Zwave-JS-UI secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

**Zwave-JS-UI**, also known under previous name ZWaveJS2MQTT, is a replacement for Openzwave. It exposes Z-Wave devices to an MQTT broker in a fully configurable manner.

To work correctly, this app require to install either
- [Domoticz package](https://github.com/YunoHost-Apps/domoticz_ynh) with **mqtt broker Mosquitto**
- [Home-Assistant package](https://github.com/YunoHost-Apps/homeassistant_ynh)


For now, although the package is fully functional (install, remove, backup, restore...), it is not integrated with domoticz and mosquitto package, this means that all settings needs to be done manually from inside the app.



**Versi terkirim:** 10.1.3~ynh1
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://zwave-js.github.io/zwave-js-ui/#/>
- Dokumentasi pengguna resmi: <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Dokumentasi admin resmi: <https://zwave-js.github.io/zwave-js-ui/#/>
- Depot kode aplikasi hulu: <https://github.com/zwave-js/zwave-js-ui>
- Gudang YunoHost: <https://apps.yunohost.org/app/zwave-js-ui>
- Laporkan bug: <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
atau
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
