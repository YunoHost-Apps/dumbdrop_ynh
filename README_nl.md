<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# DumbDrop voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/dumbdrop)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![DumbDrop met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je DumbDrop snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 1.0.0~ynh1

## Schermafdrukken

![Schermafdrukken van DumbDrop](./doc/screenshots/screeshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://www.dumbware.io/>
- Upstream app codedepot: <https://github.com/DumbWareio/DumbDrop>
- YunoHost-store: <https://apps.yunohost.org/app/dumbdrop>
- Meld een bug: <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
of
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
