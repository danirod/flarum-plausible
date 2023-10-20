# Plausible

![License](https://img.shields.io/badge/license-MIT-blue.svg) [![Latest Stable Version](https://img.shields.io/packagist/v/danirod/flarum-plausible.svg)](https://packagist.org/packages/danirod/flarum-plausible) [![Total Downloads](https://img.shields.io/packagist/dt/danirod/flarum-plausible.svg)](https://packagist.org/packages/danirod/flarum-plausible)

A [Flarum](http://flarum.org) extension. Integrate Plausible Analytics with Flarum.

[Plausible](https://plausible.io/) is a privacy-friendly Google Analytics alternative. It is a more lightweight, it doesn't use cookies and it is fully compliant with regulations like GDPR or CCPA.

## Features

* Add the HTML code for tracking automatically rather than having to add the snippet manually.
* Support for [proxies](https://plausible.io/docs/proxy/introduction) as a way to avoid adblockers blocking the tracking code, allowing to swap the domain that is serving the integration code by a custom one.
* Allow admins to be excluded from the data tracking, in order to avoid skewing the statistics on small forums.

## Motivation

I made this plugin because I manage a small Flarum forum and I wanted to get into plugin development. This plugin is simple and only does one single thing, but it already has teached some important aspects of plugin development. I am also a Plausible user and every time I changed some settings and then browsed the forum to test my changes, my session was included in the stats and I wanted a way to exclude myself.

## Installation

Install with composer:

```sh
composer require danirod/flarum-plausible:"*"
```

## Updating

```sh
composer update danirod/flarum-plausible:"*"
php flarum migrate
php flarum cache:clear
```

## Links

- [Packagist](https://packagist.org/packages/danirod/flarum-plausible)
- [GitHub](https://github.com/danirod/flarum-plausible)
- [Discuss](https://discuss.flarum.org/d/33499-plausible-analytics)
