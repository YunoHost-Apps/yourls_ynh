<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Yourls pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/yourls)](https://ci-apps.yunohost.org/ci/apps/yourls/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/yourls)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/yourls)

[![Installer Yourls avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yourls)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Yourls rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

YOURLS stands for Your Own URL Shortener. It is a small set of PHP scripts that will allow you to run your own URL shortening service (a la TinyURL or bitly).
Running your own URL shortener is fun, geeky and useful: you own your data and don't depend on third-party services. It's also a great way to add branding to your short URLs, instead of using the same public URL shortener everyone uses.

### Features

- Private (your links only) or Public (everybody can create short links, fine for an intranet)
- Dozens of plugins to easily implement new features
- Handy bookmarklets to easily shorten and share links
- Awesome stats: historical click reports, referrers tracking, visitors geo-location
- Developer API to integrate YOURLS into other applications
- Sample files to create your own public interface


**Version incluse :** 1.9.2~ynh6

**Démo :** <https://yourls.org/cookie+>

## Captures d’écran

![Capture d’écran de Yourls](./doc/screenshots/p4.png)

## Documentations et ressources

- Site officiel de l’app : <https://yourls.org/>
- Documentation officielle de l’admin : <https://docs.yourls.org/>
- Dépôt de code officiel de l’app : <https://github.com/YOURLS/YOURLS>
- YunoHost Store : <https://apps.yunohost.org/app/yourls>
- Signaler un bug : <https://github.com/YunoHost-Apps/yourls_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/yourls_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
ou
sudo yunohost app upgrade yourls -u https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
