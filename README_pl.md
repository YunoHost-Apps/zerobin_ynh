<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Zerobin dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/zerobin)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
![Status działania](https://apps.yunohost.org/badge/state/zerobin)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/zerobin)

[![Zainstaluj Zerobin z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Zerobin na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Dostarczona wersja:** 1.7.6~ynh1

**Demo:** <https://privatebin.net/>

## Zrzuty ekranu

![Zrzut ekranu z Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Niepożądane funkcje

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://privatebin.info/>
- Oficjalna dokumentacja dla administratora: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repozytorium z kodem źródłowym: <https://github.com/PrivateBin/PrivateBin>
- Sklep YunoHost: <https://apps.yunohost.org/app/zerobin>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
lub
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
