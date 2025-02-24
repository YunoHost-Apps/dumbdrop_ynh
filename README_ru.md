<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# DumbDrop для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![Состояние работы](https://apps.yunohost.org/badge/state/dumbdrop)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![Установите DumbDrop с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить DumbDrop быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A stupid simple file upload application that provides a clean, modern interface for dragging and dropping files. Built with Node.js and vanilla JavaScript.

### Features

    🚀 Drag and drop file uploads
    📁 Multiple file selection
    🎨 Clean, responsive UI with Dark Mode
    📦 Docker support with easy configuration
    📂 Directory upload support (maintains structure)
    🔒 Optional PIN protection
    📱 Mobile-friendly interface
    🔔 Configurable notifications via Apprise
    ⚡ Zero dependencies on client-side
    🛡️ Built-in security features
    💾 Configurable file size limits
    🎯 File extension filtering


**Поставляемая версия:** 1.0.0~ynh1

## Снимки экрана

![Снимок экрана DumbDrop](./doc/screenshots/screeshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.dumbware.io/>
- Репозиторий кода главной ветки приложения: <https://github.com/DumbWareio/DumbDrop>
- Магазин YunoHost: <https://apps.yunohost.org/app/dumbdrop>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
или
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
