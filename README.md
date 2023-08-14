<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Pelican for YunoHost

[![Integration level](https://dash.yunohost.org/integration/hugo.svg)](https://dash.yunohost.org/appci/app/hugo) ![Working status](https://ci-apps.yunohost.org/ci/badges/hugo.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/hugo.maintain.svg)

[![Install Pelican with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=hugo)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Pelican quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Hugo is a static site generator written in Go, optimized for speed and designed for flexibility. With its advanced templating system and fast asset pipelines, Hugo renders a complete site in seconds, often less.

Due to its flexible framework, multilingual support, and powerful taxonomy system, Hugo is widely used to create:

- Corporate, government, nonprofit, education, news, event, and project sites
- Documentation sites
- Image portfolios
- Landing pages
- Business, professional, and personal blogs
- Resumes and CVs

Use Hugo's embedded web server during development to instantly see changes to content, structure, behavior, and presentation. Then deploy the site to your host, or push changes to your Git provider for automated builds and deployment.

Hugo's fast asset pipelines include:

- CSS bundling – transpilation (Sass), tree shaking, minification, source maps, SRI hashing, and PostCSS integration
- JavaScript bundling – transpilation (TypeScript, JSX), tree shaking, minification, source maps, and SRI hashing
- Image processing – convert, resize, crop, rotate, adjust colors, apply filters, overlay text and images, and extract EXIF data

And with Hugo Modules, you can share content, assets, data, translations, themes, templates, and configuration with other projects via public or private Git repositories.

*from Hugo's README*

**Shipped version:** 0.117.0~ynh1
## Documentation and resources

* Official app website: <https://gohugo.io>
* Official admin documentation: <https://gohugo.io/documentation>
* Upstream app code repository: <https://github.com/gohugoio/hugo>
* YunoHost documentation for this app: <https://yunohost.org/app_hugo>
* Report a bug: <https://github.com/YunoHost-Apps/hugo_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/hugo_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/hugo_ynh/tree/testing --debug
or
sudo yunohost app upgrade hugo -u https://github.com/YunoHost-Apps/hugo_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>