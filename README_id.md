<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# DumbDrop untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![Status kerja](https://apps.yunohost.org/badge/state/dumbdrop)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![Pasang DumbDrop dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang DumbDrop secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A stupid simple file upload application that provides a clean, modern interface for dragging and dropping files. Built with Node.js and vanilla JavaScript.

### Features

- Drag and drop file uploads
- Multiple file selection
- Clean, responsive UI with Dark Mode
- Docker support with easy configuration
- Directory upload support (maintains structure)
- Optional PIN protection
- Mobile-friendly interface
- Configurable notifications via Apprise
- Zero dependencies on client-side
- Built-in security features
- Configurable file size limits
- File extension filtering


**Versi terkirim:** 1.0.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada DumbDrop](./doc/screenshots/screeshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.dumbware.io/>
- Depot kode aplikasi hulu: <https://github.com/DumbWareio/DumbDrop>
- Gudang YunoHost: <https://apps.yunohost.org/app/dumbdrop>
- Laporkan bug: <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
