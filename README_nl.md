<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Zerobin voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/zerobin)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/zerobin)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/zerobin)

[![Zerobin met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Zerobin snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Geleverde versie:** 1.7.1~ynh2

**Demo:** <https://privatebin.net/>

## Schermafdrukken

![Schermafdrukken van Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Anti-eigenschappen

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Documentatie en bronnen

- Officiele website van de app: <https://privatebin.info/>
- Officiele beheerdersdocumentatie: <https://github.com/PrivateBin/PrivateBin/wiki>
- Upstream app codedepot: <https://github.com/PrivateBin/PrivateBin>
- YunoHost-store: <https://apps.yunohost.org/app/zerobin>
- Meld een bug: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
of
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
