# Lutim pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/lutim.svg)](https://dash.yunohost.org/appci/app/lutim) ![](https://ci-apps.yunohost.org/ci/badges/lutim.status.svg) [![](https://ci-apps.yunohost.org/ci/badges/lutim.maintain.svg)](https://github.com/YunoHost/Apps/#what-to-do-if-i-cant-maintain-my-app-anymore-)  
[![Installer Lutim avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=lutim)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Lutim rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/install_fr) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Lutim stocke les images et vous permet de les voir, de les télécharger ou de les partager sur les réseaux sociaux.
Les images sont stockées indéfiniment à moins que vous ne demandiez qu'elles soient effacées à la première vue ou après 24 heures / une semaine / un mois / un an.

**Version embarquée :** 0.12.1

## Captures d'écran

## Démo

* [Instance officielle](https://lut.im/)

## Configuration

Éditez le fichier `/var/www/lutim/lutim.conf` pour configurer Lutim.
Rechargez ensuite le service Lutim.

## Documentation

 * Documentation officielle : https://framagit.org/luc/lutim/wikis/home
 * Documentation YunoHost : https://yunohost.org/app_lutim

## Fonctionnalités spécifiques à YunoHost

#### Support multi-utilisateurs

Non applicable.

#### Architectures supportées.

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/lutim.svg)](https://ci-apps.yunohost.org/ci/apps/lutim/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/lutim.svg)](https://ci-apps-arm.yunohost.org/ci/apps/lutim/)

## Limitations

## Informations additionnelles

## Liens

 * Reporter un bug : https://github.com/YunoHost-Apps/lutim_ynh/issues
 * Site de Lutim : https://lut.im/
 * Dépôt de Lutim : https://framagit.org/fiat-tux/hat-softwares/lutim
 * Site de YunoHost : https://yunohost.org/

---

## Informations à l'intention des développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/lutim_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --force --debug
ou
sudo yunohost app upgrade lutim -u https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --debug
```
