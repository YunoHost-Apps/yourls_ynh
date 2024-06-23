<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Yourls para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/yourls.svg)](https://dash.yunohost.org/appci/app/yourls) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/yourls.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/yourls.maintain.svg)

[![Instalar Yourls con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yourls)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarYourls rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

YOURLS stands for Your Own URL Shortener. It is a small set of PHP scripts that will allow you to run your own URL shortening service (a la TinyURL or bitly).
Running your own URL shortener is fun, geeky and useful: you own your data and don't depend on third-party services. It's also a great way to add branding to your short URLs, instead of using the same public URL shortener everyone uses.

### Features

- Private (your links only) or Public (everybody can create short links, fine for an intranet)
- Dozens of plugins to easily implement new features
- Handy bookmarklets to easily shorten and share links
- Awesome stats: historical click reports, referrers tracking, visitors geo-location
- Developer API to integrate YOURLS into other applications
- Sample files to create your own public interface


**Versión actual:** 1.9.2~ynh5

**Demo:** <https://yourls.org/cookie+>

## Capturas

![Captura de Yourls](./doc/screenshots/p4.png)

## Documentaciones y recursos

- Sitio web oficial: <https://yourls.org/>
- Documentación administrador oficial: <https://docs.yourls.org/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/YOURLS/YOURLS>
- Catálogo YunoHost: <https://apps.yunohost.org/app/yourls>
- Reportar un error: <https://github.com/YunoHost-Apps/yourls_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/yourls_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
o
sudo yunohost app upgrade yourls -u https://github.com/YunoHost-Apps/yourls_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
