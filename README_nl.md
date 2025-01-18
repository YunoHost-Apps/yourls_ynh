<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Yourls voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/yourls)](https://ci-apps.yunohost.org/ci/apps/yourls/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/yourls)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/yourls)

[![Yourls met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yourls)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Yourls snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

YOURLS stands for Your Own URL Shortener. It is a small set of PHP scripts that will allow you to run your own URL shortening service (a la TinyURL or bitly).
Running your own URL shortener is fun, geeky and useful: you own your data and don't depend on third-party services. It's also a great way to add branding to your short URLs, instead of using the same public URL shortener everyone uses.

### Features

- Private (your links only) or Public (everybody can create short links, fine for an intranet)
- Dozens of plugins to easily implement new features
- Handy bookmarklets to easily shorten and share links
- Awesome stats: historical click reports, referrers tracking, visitors geo-location
- Developer API to integrate YOURLS into other applications
- Sample files to create your own public interface


**Geleverde versie:** 1.9.2~ynh6

**Demo:** <https://yourls.org/cookie+>

## Schermafdrukken

![Schermafdrukken van Yourls](./doc/screenshots/p4.png)

## Documentatie en bronnen

- Officiele website van de app: <https://yourls.org/>
- Officiele beheerdersdocumentatie: <https://docs.yourls.org/>
- Upstream app codedepot: <https://github.com/YOURLS/YOURLS>
- YunoHost-store: <https://apps.yunohost.org/app/yourls>
- Meld een bug: <https://github.com/YunoHost-Apps/yourls_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/yourls_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
of
sudo yunohost app upgrade yourls -u https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
