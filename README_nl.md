<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Feber voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/feber.svg)](https://ci-apps.yunohost.org/ci/apps/feber/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/feber.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/feber.maintain.svg)

[![Feber met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=feber)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Feber snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Feber is a simple, self-hostable group calendar.

### Features

- File-based and database-free - trivial to setup, backup and transfer
- Event booking, easy repetition of events
- User management (four permission levels from read-only up to admin)
- Anonymous viewing/editing link option
- ics/ical subscription link option
- Automatic dark/light theme
- Customize calendar title and start of week (Monday/Sunday)


**Geleverde versie:** 1.2.1~ynh1

**Demo:** <https://simonrepp.com/feber/demo/>

## Schermafdrukken

![Schermafdrukken van Feber](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://simonrepp.com/feber/>
- Upstream app codedepot: <https://codeberg.org/simonrepp/feber>
- YunoHost-store: <https://apps.yunohost.org/app/feber>
- Meld een bug: <https://github.com/YunoHost-Apps/feber_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/feber_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
of
sudo yunohost app upgrade feber -u https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
