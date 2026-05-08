# Animarr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/animarr.svg)](https://dash.yunohost.org/appci/app/animarr) ![Working status](https://img.shields.io/badge/Working-Yes-green) ![Maintained](https://img.shields.io/badge/Maintained-Yes-green)

[Lire ce README en français.](./README_fr.md)

This package allows you to install Animarr quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.

## Overview

Animarr is a smart Torznab proxy for Anime metadata resolution.

**Shipped version:** 1.2.1~ynh1

## Documentation and resources

- Upstream app code repository: [https://github.com/wiwileborne/Animarr](https://github.com/wiwileborne/Animarr)
- YunoHost documentation for this app: [https://yunohost.org/app_animarr](https://yunohost.org/app_animarr)
- Report a bug: [https://github.com/wiwileborne/Animarr_ynh/issues](https://github.com/wiwileborne/Animarr_ynh/issues)

## Maintainers

- wiwileborne

## Developer info

Please send your pull request to the [testing branch](https://github.com/wiwileborne/Animarr_ynh/tree/testing).

To try the testing branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/wiwileborne/Animarr_ynh/tree/testing --debug
```
or
```bash
sudo yunohost app upgrade animarr -u https://github.com/wiwileborne/Animarr_ynh/tree/testing --debug
```
