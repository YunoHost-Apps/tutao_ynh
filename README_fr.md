# Tutanota pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/Tutanota.svg)](https://dash.yunohost.org/appci/app/Tutanota) ![](https://ci-apps.yunohost.org/ci/badges/Tutanota.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/Tutanota.maintain.svg)  
[![Installer Tutanota avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=Tutanota)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Tutanota rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Tutanota is the secure email service with built-in end-to-end encryption that enables you to communicate securely with anyone on all your devices.


**Version incluse :** 3.95.1~ynh1

**Démo :** https://demo.example.com

## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

To access admin panel, use URL of the following kind: http://product_installation_URL/?admin

For example: http://webmail.domain.com/?admin

Default login is "admin", password is the one you choose during install. 

## Documentations et ressources

* Site officiel de l'app : https://github.com/tutao/tutanota
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://github.com/tutao/tutanota
* Documentation YunoHost pour cette app : https://yunohost.org/app_Tutanota
* Signaler un bug : https://github.com/YunoHost-Apps/Tutanota_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/Tutanota_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/Tutanota_ynh/tree/testing --debug
ou
sudo yunohost app upgrade Tutanota -u https://github.com/YunoHost-Apps/Tutanota_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps