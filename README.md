<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Galette for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/galette)](https://ci-apps.yunohost.org/ci/apps/galette/)
![Working status](https://apps.yunohost.org/badge/state/galette)
![Maintenance status](https://apps.yunohost.org/badge/maintained/galette)

[![Install Galette with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=galette)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Galette quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Galette is a membership management web application towards non profit organizations.

### Features

- Member management
- Management of contributions and transactions
- Management of groups and managers
- Imports and exports (open formats)
- Increased accessibility (use and compliance with web standards)
- Configuration of cards and lists
- Addition of dynamic fields to members, contributions and transactions files
- Plugin support


**Shipped version:** 1.1.3~ynh1

**Demo:** <https://demo.galette.eu/login>

## Screenshots

![Screenshot of Galette](./doc/screenshots/edit_member.png)

## Documentation and resources

- Official app website: <https://www.galette.eu>
- Official admin documentation: <https://doc.galette.eu/fr/master/>
- Upstream app code repository: <https://github.com/galette/galette>
- YunoHost Store: <https://apps.yunohost.org/app/galette>
- Report a bug: <https://github.com/YunoHost-Apps/galette_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/galette_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/galette_ynh/tree/testing --debug
or
sudo yunohost app upgrade galette -u https://github.com/YunoHost-Apps/galette_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
