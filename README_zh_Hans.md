<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Zerobin

[![集成程度](https://apps.yunohost.org/badge/integration/zerobin)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
![工作状态](https://apps.yunohost.org/badge/state/zerobin)
![维护状态](https://apps.yunohost.org/badge/maintained/zerobin)

[![使用 YunoHost 安装 Zerobin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Zerobin。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**分发版本：** 1.7.1~ynh2

**演示：** <https://privatebin.net/>

## 截图

![Zerobin 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## 文档与资源

- 官方应用网站： <https://privatebin.info/>
- 官方管理文档： <https://github.com/PrivateBin/PrivateBin/wiki>
- 上游应用代码库： <https://github.com/PrivateBin/PrivateBin>
- YunoHost 商店： <https://apps.yunohost.org/app/zerobin>
- 报告 bug： <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
或
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>