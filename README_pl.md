<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Yourls dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/yourls)](https://ci-apps.yunohost.org/ci/apps/yourls/)
![Status działania](https://apps.yunohost.org/badge/state/yourls)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/yourls)

[![Zainstaluj Yourls z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yourls)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Yourls na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

YOURLS stands for Your Own URL Shortener. It is a small set of PHP scripts that will allow you to run your own URL shortening service (a la TinyURL or bitly).
Running your own URL shortener is fun, geeky and useful: you own your data and don't depend on third-party services. It's also a great way to add branding to your short URLs, instead of using the same public URL shortener everyone uses.

### Features

- Private (your links only) or Public (everybody can create short links, fine for an intranet)
- Dozens of plugins to easily implement new features
- Handy bookmarklets to easily shorten and share links
- Awesome stats: historical click reports, referrers tracking, visitors geo-location
- Developer API to integrate YOURLS into other applications
- Sample files to create your own public interface


**Dostarczona wersja:** 1.9.2~ynh6

**Demo:** <https://yourls.org/cookie+>

## Zrzuty ekranu

![Zrzut ekranu z Yourls](./doc/screenshots/p4.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://yourls.org/>
- Oficjalna dokumentacja dla administratora: <https://docs.yourls.org/>
- Repozytorium z kodem źródłowym: <https://github.com/YOURLS/YOURLS>
- Sklep YunoHost: <https://apps.yunohost.org/app/yourls>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/yourls_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/yourls_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
lub
sudo yunohost app upgrade yourls -u https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
