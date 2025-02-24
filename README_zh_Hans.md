<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 DumbDrop

[![集成程度](https://apps.yunohost.org/badge/integration/dumbdrop)](https://ci-apps.yunohost.org/ci/apps/dumbdrop/)
![工作状态](https://apps.yunohost.org/badge/state/dumbdrop)
![维护状态](https://apps.yunohost.org/badge/maintained/dumbdrop)

[![使用 YunoHost 安装 DumbDrop](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dumbdrop)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 DumbDrop。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 1.0.0~ynh1

## 截图

![DumbDrop 的截图](./doc/screenshots/screeshot.png)

## 文档与资源

- 官方应用网站： <https://www.dumbware.io/>
- 上游应用代码库： <https://github.com/DumbWareio/DumbDrop>
- YunoHost 商店： <https://apps.yunohost.org/app/dumbdrop>
- 报告 bug： <https://github.com/YunoHost-Apps/dumbdrop_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
或
sudo yunohost app upgrade dumbdrop -u https://github.com/YunoHost-Apps/dumbdrop_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
