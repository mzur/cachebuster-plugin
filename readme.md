# Kirby Cachebuster Plugin

This plugin will add modification timestamps to your css and js files,
as long as they are embedded with the css() and js() helpers.

## Requirements

This plugin requires Kirby 2.3. Older Kirby 2 versions are supported by version 2.0.0 of this plugin.

Please note that this plugin doesn't add caching headers to your CSS and JS files.
To make proper use of this plugin, you need to add caching rules to your server configuration.

## Installation

To use this plugin, add the cachebuster.php to `site/plugins`.
After that you must add rules to your htaccess file or your nginx configuration (see below).

Now you can activate the plugin with following line in your `config.php`.

```
c::set('cachebuster', true);
```

## Authors

Bastian Allgeier <bastian@getkirby.com> & Lukas Bestle <lukas@getkirby.com>
