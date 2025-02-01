<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Zerobin для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/zerobin)](https://ci-apps.yunohost.org/ci/apps/zerobin/)
![Состояние работы](https://apps.yunohost.org/badge/state/zerobin)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/zerobin)

[![Установите Zerobin с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zerobin)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Zerobin быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.


**Поставляемая версия:** 1.7.6~ynh1

**Демо-версия:** <https://privatebin.net/>

## Снимки экрана

![Снимок экрана Zerobin](./doc/screenshots/screenshot.png)

## :red_circle: Анти-функции

- **Replaced by another app**: Was replaced by another app. Please refer to the README.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://privatebin.info/>
- Официальная документация администратора: <https://github.com/PrivateBin/PrivateBin/wiki>
- Репозиторий кода главной ветки приложения: <https://github.com/PrivateBin/PrivateBin>
- Магазин YunoHost: <https://apps.yunohost.org/app/zerobin>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/zerobin_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
или
sudo yunohost app upgrade zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
