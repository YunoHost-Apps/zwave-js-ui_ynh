<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Zwave-JS-UI pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/zwave-js-ui)](https://ci-apps.yunohost.org/ci/apps/zwave-js-ui/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/zwave-js-ui)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/zwave-js-ui)

[![Installer Zwave-JS-UI avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zwave-js-ui)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Zwave-JS-UI rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

**Zwave-JS-UI**, aussi connu sous le nom de ZWaveJS2MQTT, est un remplaçant pour Openzwave. Il permet d'exposer les terminaux Z-Wave à un broker  MQTT de façon complètement configurable.

Pour fonctionner correctement, cette application nécessite d'avoir installé soit:
- le package [Domoticz](https://github.com/YunoHost-Apps/domoticz_ynh) avec le **broker MQTT mosquitto**
- le package [Home-Assistant](https://github.com/YunoHost-Apps/homeassistant_ynh)


Pour l'instant, bien que le package fonctionne (installation, désinstallation, sauvegarde, restauration...), il n'est pas intégré avec domoticz et mosquitto, les paramétrages doivent être fait manuellement depuis l'application.


**Version incluse :** 10.0.2~ynh1
## Documentations et ressources

- Site officiel de l’app : <https://zwave-js.github.io/zwave-js-ui/#/>
- Documentation officielle utilisateur : <https://www.domoticz.com/wiki/Zwave-JS-UI>
- Documentation officielle de l’admin : <https://zwave-js.github.io/zwave-js-ui/#/>
- Dépôt de code officiel de l’app : <https://github.com/zwave-js/zwave-js-ui>
- YunoHost Store : <https://apps.yunohost.org/app/zwave-js-ui>
- Signaler un bug : <https://github.com/YunoHost-Apps/zwave-js-ui_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
ou
sudo yunohost app upgrade zwave-js-ui -u https://github.com/YunoHost-Apps/zwave-js-ui_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
