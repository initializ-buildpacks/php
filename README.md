# Paketo Buildpack for PHP
## `gcr.io/paketo-buildpacks/php`

The PHP Paketo Buildpack provides a set of collaborating buildpacks that
enable the building of a PHP-based application. These buildpacks include:
- [PHP Dist CNB](https://github.com/initializ-buildpacks/php-dist)
- [PHP HTTPD CNB](https://github.com/initializ-buildpacks/php-httpd)
- [PHP Nginx CNB](https://github.com/initializ-buildpacks/php-nginx)
- [PHP Built-in Server CNB](https://github.com/initializ-buildpacks/php-builtin-server)
- [PHP FPM CNB](https://github.com/initializ-buildpacks/php-fpm)
- [PHP Start CNB](https://github.com/initializ-buildpacks/php-start)
- [PHP Redis Session Handler CNB](https://github.com/initializ-buildpacks/php-redis-session-handler)
- [PHP Memcached Session Handler CNB](https://github.com/initializ-buildpacks/php-memcached-session-handler)
- [Composer CNB](https://github.com/initializ-buildpacks/composer)
- [Composer Install CNB](https://github.com/initializ-buildpacks/composer-install)
- [Apache HTTPD CNB](https://github.com/initializ-buildpacks/httpd)
- [NGINX CNB](https://github.com/paketo-buildpacks/nginx)

The buildpack supports building PHP console and web applications. Web
applications can be run on either the [built-in PHP
webserver](https://www.php.net/manual/en/features.commandline.webserver.php),
[Apache HTTPD](https://httpd.apache.org/) or [NGINX](https://www.nginx.com/).
The buildpack also provides optional support for the utilization of
[Composer](https://getcomposer.org) as a package manager.

Usage examples can be found in the
[`samples` repository under the `php` directory](https://github.com/paketo-buildpacks/samples/tree/main/php).

This buildpack also includes the following utility buildpacks:
- [Procfile CNB](https://github.com/paketo-buildpacks/procfile)
- [Environment Variables CNB](https://github.com/paketo-buildpacks/environment-variables)
- [Image Labels CNB](https://github.com/paketo-buildpacks/image-labels)
- [CA Certificates CNB](https://github.com/paketo-buildpacks/ca-certificates)

#### The PHP buildpack is compatible with the following builder(s):

- [Paketo Jammy Full Builder](https://github.com/paketo-buildpacks/builder-jammy-full)
- [Paketo Bionic Full Builder](https://github.com/paketo-buildpacks/full-builder)

#### Docs

Check out the [PHP Paketo Buildpack
docs](https://paketo.io/docs/buildpacks/language-family-buildpacks/php) for
more information
