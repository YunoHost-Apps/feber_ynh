<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Feber for YunoHost

[![Integration level](https://dash.yunohost.org/integration/feber.svg)](https://ci-apps.yunohost.org/ci/apps/feber/) ![Working status](https://ci-apps.yunohost.org/ci/badges/feber.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/feber.maintain.svg)

[![Install Feber with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=feber)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Feber quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Feber is a simple, self-hostable group calendar.

### Features

- File-based and database-free - trivial to setup, backup and transfer
- Event booking, easy repetition of events
- User management (four permission levels from read-only up to admin)
- Anonymous viewing/editing link option
- ics/ical subscription link option
- Automatic dark/light theme
- Customize calendar title and start of week (Monday/Sunday)


**Shipped version:** 1.2.5~ynh1

**Demo:** <https://simonrepp.com/feber/demo/>

## Screenshots

![Screenshot of Feber](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://simonrepp.com/feber/>
- Upstream app code repository: <https://codeberg.org/simonrepp/feber>
- YunoHost Store: <https://apps.yunohost.org/app/feber>
- Report a bug: <https://github.com/YunoHost-Apps/feber_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/feber_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
or
sudo yunohost app upgrade feber -u https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
