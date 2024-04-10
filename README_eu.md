<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zerobin YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/zerobin.svg)](https://dash.yunohost.org/appci/app/zerobin) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/zerobin.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/zerobin.maintain.svg)

[![Instalatu Zerobin YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zerobin YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Paketatutako bertsioa:** 1.7.1~ynh1

**Demoa:** <https://privatebin.net/>

## Pantaila-argazkiak

![Zerobin(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Beste aplikazio batek ordeztu du**: Beste aplikazio batek ordeztu du. Irakurri README fitxategia.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://privatebin.info/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/PrivateBin/PrivateBin/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/PrivateBin/PrivateBin>
- YunoHost Denda: <https://apps.yunohost.org/app/zerobin>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
