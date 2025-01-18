<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Yourls para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/yourls)](https://ci-apps.yunohost.org/ci/apps/yourls/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/yourls)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/yourls)

[![Instalar Yourls con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yourls)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Yourls de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

YOURLS stands for Your Own URL Shortener. It is a small set of PHP scripts that will allow you to run your own URL shortening service (a la TinyURL or bitly).
Running your own URL shortener is fun, geeky and useful: you own your data and don't depend on third-party services. It's also a great way to add branding to your short URLs, instead of using the same public URL shortener everyone uses.

### Features

- Private (your links only) or Public (everybody can create short links, fine for an intranet)
- Dozens of plugins to easily implement new features
- Handy bookmarklets to easily shorten and share links
- Awesome stats: historical click reports, referrers tracking, visitors geo-location
- Developer API to integrate YOURLS into other applications
- Sample files to create your own public interface


**Versión proporcionada:** 1.9.2~ynh6

**Demo:** <https://yourls.org/cookie+>

## Capturas de pantalla

![Captura de pantalla de Yourls](./doc/screenshots/p4.png)

## Documentación e recursos

- Web oficial da app: <https://yourls.org/>
- Documentación oficial para admin: <https://docs.yourls.org/>
- Repositorio de orixe do código: <https://github.com/YOURLS/YOURLS>
- Tenda YunoHost: <https://apps.yunohost.org/app/yourls>
- Informar dun problema: <https://github.com/YunoHost-Apps/yourls_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/yourls_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
ou
sudo yunohost app upgrade yourls -u https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
