# Headache

> An easy-to-swallow painkiller plugin for WordPress.

The plugin removes a lot of default WordPress stuff you just can't wait to get rid of. It removes meta tags such as feeds, version numbers and emojis.

[![Monthly Downloads](https://badgen.net/packagist/dm/wordplate/headache)](https://packagist.org/packages/wordplate/headache/stats)
[![Latest Version](https://badgen.net/packagist/v/wordplate/headache)](https://packagist.org/packages/wordplate/headache)

## Installation

Require the package, with Composer, in the root directory of your project.

```sh
composer require wordplate/headache
```

Then login to the WordPress administrator dashboard and active the plugin.

## Features

All features are activated by default when the plugin is activated.

- Disables feeds
- Disable XML RPC for security
- Removes WordPress version
- Removes shortlink
- Disables comments feeds
- Removes RSS feed links
- Removes all extra RSS feed links
- Removes Really Simple Discovery link
- Removes wlwmanifest.xml
- Removes meta rel=dns-prefetch href=//s.w.org
- Removes relational links for the posts
- Removes REST API link tag from header
- Removes emojis
- Removes oEmbeds
- Disable default users API endpoints for security
- Removes JPEG compression
- Update login page image link URL
- Update login page link title
- Removes ?ver= query from styles and scripts
- Remove contributor, subscriber and author roles
