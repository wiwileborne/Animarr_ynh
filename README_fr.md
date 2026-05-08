# Animarr pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/animarr.svg)](https://dash.yunohost.org/appci/app/animarr) ![Statut de fonctionnement](https://img.shields.io/badge/Fonctionne-Oui-green) ![Maintenu](https://img.shields.io/badge/Maintenu-Oui-green)

Animarr est un proxy Torznab intelligent pour la résolution de métadonnées d'Anime.

Ce package vous permet d'installer Animarr rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, veuillez consulter [le guide](https://yunohost.org/#/install) pour apprendre à l'installer.

## Aperçu

Animarr résout le décalage entre les noms des releases (scène) et les fournisseurs de métadonnées (AniList, MAL, TMDB).

**Version embarquée :** 1.2.1~ynh1

## Documentation et ressources

- Dépôt de code de l'application : [https://github.com/wiwileborne/Animarr](https://github.com/wiwileborne/Animarr)
- Documentation YunoHost pour cette application : [https://yunohost.org/app_animarr](https://yunohost.org/app_animarr)
- Signaler un bug : [https://github.com/wiwileborne/Animarr_ynh/issues](https://github.com/wiwileborne/Animarr_ynh/issues)

## Mainteneurs

- wiwileborne

## Informations pour les développeurs

Veuillez envoyer vos pull requests vers la [branche testing](https://github.com/wiwileborne/Animarr_ynh/tree/testing).

Pour tester la branche testing, procédez comme suit :

```bash
sudo yunohost app install https://github.com/wiwileborne/Animarr_ynh/tree/testing --debug
```
ou
```bash
sudo yunohost app upgrade animarr -u https://github.com/wiwileborne/Animarr_ynh/tree/testing --debug
```
