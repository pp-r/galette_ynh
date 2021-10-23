<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Galette for YunoHost

[![Integration level](https://dash.yunohost.org/integration/galette.svg)](https://dash.yunohost.org/appci/app/galette) ![](https://ci-apps.yunohost.org/ci/badges/galette.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/galette.maintain.svg)  
[![Install Galette with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=galette)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Galette quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Membership management web application for non profit organizations

**Shipped version:** 0.9.5.1~ynh1

**Demo:** https://demo.galette.eu/login

## Screenshots

![](./doc/screenshots/edit_member.png)

## Disclaimers / important information

## Configuration

1. The app will require to complete the registration process after the instllation is complete by visiting the domain on which Galette is installed.
1. The Postgresql database credentials will be sent to the admin mail. Fill these details while doing the registration process.

## Documentation and resources

* Official app website: https://www.galette.eu
* Official user documentation: https://yunohost.org/apps
* Official admin documentation: https://doc.galette.eu/fr/master/
* Upstream app code repository: https://github.com/galette/galette
* YunoHost documentation for this app: https://yunohost.org/app_galette
* Report a bug: https://github.com/YunoHost-Apps/galette_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/galette_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/galette_ynh/tree/testing --debug
or
sudo yunohost app upgrade galette -u https://github.com/YunoHost-Apps/galette_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
