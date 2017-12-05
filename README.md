# Lutim for YunoHost

[![Integration level](https://dash.yunohost.org/integration/lutim.svg)](https://ci-apps.yunohost.org/jenkins/job/lutim%20%28Community%29/lastBuild/consoleFull)  
[![Install Lutim with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=lutim)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Lutim quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Lutim stores images and allows you to see them, download them or share them on social networks.
Images are indefinitely stored unless you request that they will be deleted at first view or after 24 hours / one week / one month / one year.

**Shipped version:** 0.8.6

## Screenshots

## Configuration

Edit the file `/var/www/lutim/lutim.conf` to edit the configuration of Lutim.
Then reload the lutim service.

## Documentation

 * Official documentation: https://framagit.org/luc/lutim/wikis/home
 * YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Not relevant.

#### Supported architectures

* Tested on x86_64

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/lutim_ynh/issues
 * Lutim website: https://lut.im/
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/lutim_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --verbose
or
sudo yunohost app upgrade lutim -u https://github.com/YunoHost-Apps/lutim_ynh/tree/testing --verbose
```
