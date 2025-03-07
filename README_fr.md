# Invidious pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/invidious.svg)](https://dash.yunohost.org/appci/app/invidious) ![](https://ci-apps.yunohost.org/ci/badges/invidious.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/invidious.maintain.svg)  
[![Installer Invidious avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=invidious)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Invidious rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Invidious est une interface permettant d'accéder aux vidéos Youtube sans passer par youtube.com
En plus de constituer un avantage sur le plan de la confidentialité (les données ne transitent pas directement par les services du géant), cette interface offre plusieurs fonctionnalités :
- Mode audio seul,
- Mode sombre,
- Possibilité d'afficher les commentaires Reddit plutôt que les commentaires YouTube,
- Possibilité de s'abonner aux chaines sans créer de compte Google

**Version incluse :** 22.02.08~ynh1

**Démo :** https://invidious.site/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## Configuration

Vous pouvez configurer Invidious en modifiant le fichier de configuration `/var/www/invidious/config/config.yaml` avec l'aide de cette [documentation](https://docs.invidious.io/Configuration.md).

## Limitations

* Invidious a besoin de plus de 3Go de RAM pour être installé.

## Documentations et ressources

* Documentation officielle utilisateur : https://github.com/iv-org/documentation
* Documentation officielle de l'admin : https://docs.invidious.io/
* Dépôt de code officiel de l'app : https://github.com/iv-org/invidious
* Documentation YunoHost pour cette app : https://yunohost.org/app_invidious
* Signaler un bug : https://github.com/YunoHost-Apps/invidious_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/invidious_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/invidious_ynh/tree/testing --debug
ou
sudo yunohost app upgrade invidious -u https://github.com/YunoHost-Apps/invidious_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps