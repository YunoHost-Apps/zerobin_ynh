<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Zerobin untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/zerobin.svg)](https://ci-apps.yunohost.org/ci/apps/zerobin/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/zerobin.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/zerobin.maintain.svg)

[![Pasang Zerobin dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Zerobin secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Versi terkirim:** 1.7.1~ynh1

**Demo:** <https://privatebin.net/>

## Tangkapan Layar

![Tangkapan Layar pada Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://privatebin.info/>
- Dokumentasi admin resmi: <https://github.com/PrivateBin/PrivateBin/wiki>
- Depot kode aplikasi hulu: <https://github.com/PrivateBin/PrivateBin>
- Gudang YunoHost: <https://apps.yunohost.org/app/zerobin>
- Laporkan bug: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
atau
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
