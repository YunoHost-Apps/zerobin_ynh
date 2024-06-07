<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Zerobin para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/zerobin.svg)](https://dash.yunohost.org/appci/app/zerobin) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/zerobin.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/zerobin.maintain.svg)

[![Instalar Zerobin con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Zerobin de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Versión proporcionada:** 1.7.1~ynh1

**Demo:** <https://privatebin.net/>

## Capturas de pantalla

![Captura de pantalla de Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Debes considerar

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Documentación e recursos

- Web oficial da app: <https://privatebin.info/>
- Documentación oficial para admin: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repositorio de orixe do código: <https://github.com/PrivateBin/PrivateBin>
- Tenda YunoHost: <https://apps.yunohost.org/app/zerobin>
- Informar dun problema: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
