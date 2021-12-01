<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Matomo for YunoHost

[![Integration level](https://dash.yunohost.org/integration/matomo.svg)](https://dash.yunohost.org/appci/app/matomo) ![](https://ci-apps.yunohost.org/ci/badges/matomo.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/matomo.maintain.svg)  
[![Install Matomo with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matomo)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Matomo quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Open source analytics platform for measuring Web statistics

**Shipped version:** 4.6.1~ynh1

**Demo:** https://demo.matomo.org

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

1. The app will require to complete the registration process after the instllation is complete by **visiting the domain** on  which Matomo is installed.
1. The MySQL database credentials will be sent to the **admin mail**. Fill these details while doing the registration process.
1. No LDAP support yet for the app.

## Documentation and resources

* Official app website: https://matomo.org
* Official admin documentation: https://matomo.org/docs
* Upstream app code repository: https://github.com/matomo-org/matomo
* YunoHost documentation for this app: https://yunohost.org/app_matomo
* Report a bug: https://github.com/YunoHost-Apps/matomo_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/matomo_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
or
sudo yunohost app upgrade matomo -u https://github.com/YunoHost-Apps/matomo_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps