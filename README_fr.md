# Lutim pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/lutim.svg)](https://ci-apps.yunohost.org/jenkins/job/lutim%20%28Community%29/lastBuild/consoleFull)  
[![Installer Lutim avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=lutim)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Lutim rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé

Lutim stocke les images et vous permet de les voir, de les télécharger ou de les partager sur les réseaux sociaux.
Les images sont stockées indéfiniment à moins que vous ne demandiez qu'elles soient effacées à la première vue ou après 24 heures / une semaine / un mois / un an.

**Version embarquée:** 0.9.3

## Captures d'écran

## Configuration

Editez le fichier `/var/www/lutim/lutim. conf` pour éditer la configuration de Lutim.
Rechargez ensuite le service lutim.

## Documentation

 * Documentation officielle: https://framagit.org/luc/lutim/wikis/home
 * Documentation YunoHost: Il n'y a pas d'autre documentation, n'hésitez pas à contribuer.

## Fonctionnalités spécifiques à YunoHost

#### Support multi-utilisateurs

Non applicable.

#### Architectures supportées.

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/lutim%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/lutim%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/lutim%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/lutim%20(Community)%20(%7EARM%7E)/)

## Limitations

## Informations additionnelles

## Liens

 * Reporter un bug: https://github.com/YunoHost-Apps/lutim_ynh/issues
 * Site de Lutim: https://lut.im/
 * Site de YunoHost: https://yunohost.org/

---

Informations à l'intention des développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/lutim_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --verbose
ou
sudo yunohost app upgrade lutim -u https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --verbose
```
