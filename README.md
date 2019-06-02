# PrivateBin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/zerobin.svg)](https://dash.yunohost.org/appci/app/zerobin)  
[![Install PrivateBin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=zerobin)

> *This package allow you to install PrivateBin quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.

**Shipped version:** 1.1.1

## Screenshots

![](https://privatebin.info/img/1.0/bootstrap.png)

## Demo

* [YunoHost demo](https://demo.yunohost.org/zerobin/)
* [Official demo](https://privatebin.net/)

## Configuration

## Documentation

 * Official documentation: https://github.com/PrivateBin/PrivateBin/wiki

## YunoHost specific features

#### Multi-users support

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/zerobin%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/zerobin%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/zerobin/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/zerobin%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/zerobin/)

## Limitations

## Additional information

In the [update documentation](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) of Parsebin, it is specified that:

For full compatibility with ZeroBin and to be able to decrypt old pastes, you would enable this option. However this is not recommend for new installations as it weakens the security of your PrivateBin instance.

This means that we have decided to delete the directory that allows us to save the data. You can save the 'data' directory, if you want to keep your data. But you should know that this weakens the security of this application.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/zerobin_ynh/issues
 * PrivateBin website: https://privatebin.info/
 * PrivateBin repository: https://github.com/PrivateBin/PrivateBin
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
or
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```
