<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Feber

[![集成程度](https://dash.yunohost.org/integration/feber.svg)](https://ci-apps.yunohost.org/ci/apps/feber/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/feber.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/feber.maintain.svg)

[![使用 YunoHost 安装 Feber](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=feber)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Feber。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

### Features

- File-based and database-free - trivial to setup, backup and transfer
- Event booking, easy repetition of events
- User management (four permission levels from read-only up to admin)
- Anonymous viewing/editing link option
- ics/ical subscription link option
- Automatic dark/light theme
- Customize calendar title and start of week (Monday/Sunday)


**分发版本：** 1.1.1~ynh1

**演示：** <https://simonrepp.com/feber/demo/>

## 截图

![Feber 的截图](./doc/screenshots/readme.png)

## 文档与资源

- 官方应用网站： <https://simonrepp.com/feber/>
- 上游应用代码库： <https://codeberg.org/simonrepp/feber>
- YunoHost 商店： <https://apps.yunohost.org/app/feber>
- 报告 bug： <https://github.com/YunoHost-Apps/feber_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/feber_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
或
sudo yunohost app upgrade feber -u https://github.com/YunoHost-Apps/feber_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
