<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Feber для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/feber.svg)](https://ci-apps.yunohost.org/ci/apps/feber/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/feber.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/feber.maintain.svg)

[![Установите Feber с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=feber)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Feber быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Feber is a simple, self-hostable group calendar.

### Features

- File-based and database-free - trivial to setup, backup and transfer
- Event booking, easy repetition of events
- User management (four permission levels from read-only up to admin)
- Anonymous viewing/editing link option
- ics/ical subscription link option
- Automatic dark/light theme
- Customize calendar title and start of week (Monday/Sunday)


**Поставляемая версия:** 1.2.5~ynh1

**Демо-версия:** <https://simonrepp.com/feber/demo/>

## Снимки экрана

![Снимок экрана Feber](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://simonrepp.com/feber/>
- Репозиторий кода главной ветки приложения: <https://codeberg.org/simonrepp/feber>
- Магазин YunoHost: <https://apps.yunohost.org/app/feber>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/feber_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/feber_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
или
sudo yunohost app upgrade feber -u https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
