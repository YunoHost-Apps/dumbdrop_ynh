<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# DumbDrop para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![Estado funcional](https://apps.yunohost.org/badge/state/dumbdrop)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![Instalar DumbDrop con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDumbDrop rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 1.0.0~ynh1

## Capturas

![Captura de DumbDrop](./doc/screenshots/screeshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://www.dumbware.io/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/DumbWareio/DumbDrop>
- Catálogo YunoHost: <https://apps.yunohost.org/app/dumbdrop>
- Reportar un error: <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
o
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
