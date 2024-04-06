<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Zerobin per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/zerobin.svg)](https://dash.yunohost.org/appci/app/zerobin) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/zerobin.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/zerobin.maintain.svg)

[![Installa Zerobin con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Zerobin su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Versione pubblicata:** 1.3.5~ynh3

**Prova:** <https://privatebin.net/>

## Screenshot

![Screenshot di Zerobin](./doc/screenshots/screenshot.png)

## Attenzione/informazioni importanti

## Additional information

In the [update documentation](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) of PrivateBin, it is specified that:

For full compatibility with ZeroBin and to be able to decrypt old pastes, you would enable this option. However this is not recommend for new installations as it weakens the security of your PrivateBin instance.

This means that we have decided to delete the directory that allows us to save the data. You can save the 'data' directory, if you want to keep your data. But you should know that this weakens the security of this application.

## :red_circle: Anti-funzionalità

- **Sostituita da un’altra app**: Quest’app è stata sostituita da un’altra app. Fare riferimento al file “README”.

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://privatebin.info/>
- Documentazione ufficiale per gli amministratori: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repository upstream del codice dell’app: <https://github.com/PrivateBin/PrivateBin>
- Store di YunoHost: <https://apps.yunohost.org/app/zerobin>
- Segnala un problema: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
o
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
