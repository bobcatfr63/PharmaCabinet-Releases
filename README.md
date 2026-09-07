# PharmaCabinet Releases

Dépôt public de diffusion des versions installables de **PharmaCabinet**.

Ce dépôt ne contient pas le code source privé de l'application. Il sert uniquement de canal public pour :

- le manifeste de mise à jour `latest.json` ;
- les APK publiés dans GitHub Releases ;
- les notes de version.

## Convention de publication

Chaque version doit publier un asset nommé exactement :

`PharmaCabinet.apk`

Le manifeste `latest.json` pointe vers :

`https://github.com/bobcatfr63/PharmaCabinet-Releases/releases/latest/download/PharmaCabinet.apk`

Le champ `versionCode` doit toujours être supérieur à celui de la version installée pour déclencher une proposition de mise à jour.

## Sécurité

Aucun jeton GitHub privé ne doit être intégré dans l'APK. Le dépôt principal peut rester privé ; seuls les binaires destinés aux utilisateurs sont exposés ici.
