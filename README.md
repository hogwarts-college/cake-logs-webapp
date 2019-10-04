# CakePHP logs collector

:jack_o_lantern: CakePHP logs collector is a self-hosted logs collector you can connect (through a plugin) to any app and blog sites in a production/development state running primarly on CakePHP.
With CakePHP logs collector you can sort all logs by levels known by CakePHP, and generate reports as well as statistics. CakePHP will forever stay open source.
In future releases, the ability to be notified for logs by email will be added.


## Installation

1. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist cakephp/app [app_name]`.

If Composer is installed globally, run

```bash
composer create-project --prefer-dist cakephp/app
```

In case you want to use a different directory name (e.g. `/myapp/`):

```bash
composer create-project --prefer-dist cakephp/app myapp
```

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server -p 8765
```

Then you will be able to visit `http://localhost:8765` and see the welcome page.

## Update

Since this skeleton is a starting point for your application and various files
would have been modified as per your needs, there isn't a way to provide
automated updates, so you must to perform any updates manually.

## Configuration

Read and edit `config/app.php` and setup the `'Datasources'` and any other
configuration relevant for your application.

## Layout

The app skeleton uses a subset of [Foundation](http://foundation.zurb.com/) (v5) CSS
framework by default. You can, however, replace it with any other library or
custom styles.
