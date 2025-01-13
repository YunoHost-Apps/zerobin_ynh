<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Zerobin para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/zerobin)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
![Estado funcional](https://apps.yunohost.org/badge/state/zerobin)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/zerobin)

[![Instalar Zerobin con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarZerobin rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Versión actual:** 1.7.1~ynh2

**Demo:** <https://privatebin.net/>

## Capturas

![Captura de Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Documentaciones y recursos

- Sitio web oficial: <https://privatebin.info/>
- Documentación administrador oficial: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/PrivateBin/PrivateBin>
- Catálogo YunoHost: <https://apps.yunohost.org/app/zerobin>
- Reportar un error: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
o
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
