# Zerobin for Yunohost

[![Install PrivateBin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=zerobin)

## Zerobin c'est quoi ?

PrivateBin est un pastebin en ligne open source minimaliste où le serveur n'a aucune connaissance des données collées.

Les données sont chiffrées / déchiffrées dans le navigateur à l'aide de 256bit AES en mode Galois Counter.

C'est un fork de ZeroBin, développée à l'origine par Sébastien Sauvage. Il a été recodé pour permettre des extensions plus faciles et plus propres et a maintenant beaucoup plus de fonctionnalités que l'original. Cependant, il est encore entièrement compatible avec le système de stockage de données original ZeroBin 0.19. Par conséquent, de telles installations peuvent être mises à niveau vers ce fork sans perdre de données.

Source: [privatebin.info](https://privatebin.info)

### Installation

`$ sudo yunohost app install zerobin`

### Mise à jour

`$ sudo yunohost app upgrade --verbose zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh.git`

### Recommendation

Dans la [documentation de mise à jour](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) de Parsebin, il est précisé que :

> Pour une compatibilité totale avec ZeroBin et pour pouvoir décrypter les anciennes données, vous autoriseriez cette option. Cependant, cela n'est pas recommandé pour les nouvelles installations car cela affaiblit la sécurité de votre instance PrivateBin.

Ce qui veut dire que nous avons pris le parti de supprimer le répertoire qui permet de sauvegarder les données. Vous pouvez sauvegarder le répertoire 'data', si vous souhaitez concerver vos données. Mais vous devez savoir que celà affaibli la sécurité de cette application.

## What is PrivateBin?

PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data.

Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.

This is a fork of ZeroBin, originally developed by Sébastien Sauvage. It was refactored to allow easier and cleaner extensions and has now much more features than the original. It is however still fully compatible to the original ZeroBin 0.19 data storage scheme. Therefore such installations can be upgraded to this fork without loosing any data.

Source: [privatebin.info](https://privatebin.info)

### Install

`$ sudo yunohost app install zerobin`

### Update

`$ sudo yunohost app upgrade --verbose zerobin -u https://github.com/YunoHost-Apps/zerobin_ynh.git`

### Recommandation

In the [update documentation] (https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) of Parsebin, it is specified that:

For full compatibility with ZeroBin and to be able to decrypt old pastes, you would enable this option. However this is not recommend for new installations as it weakens the security of your PrivateBin instance.

This means that we have decided to delete the directory that allows us to save the data. You can save the 'data' directory, if you want to keep your data. But you should know that this weakens the security of this application.