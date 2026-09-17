# WP Post Views

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/tikhomirov/wp-postviews-plugin/releases)
[![WordPress](https://img.shields.io/badge/WordPress-4.6%2B-blue.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-purple.svg)](https://php.net/)

Post view counter for WordPress. Tracks views per post type when enabled via theme support.

## Requirements

| Component | Minimum |
|-----------|---------|
| **WordPress** | 4.6 |
| **PHP** | 7.4 |

## Features

- View counter stored in post meta
- Theme support gate: `add_theme_support('views')`
- Admin column and template helpers
- Composer package `rwsite/wp-postviews-plugin`

## Installation

### Composer

```bash
composer require rwsite/wp-postviews-plugin
```

### Manual

1. Download the [latest release](https://github.com/tikhomirov/wp-postviews-plugin/releases).
2. Upload to `wp-content/plugins/wp-postviews-plugin/`.
3. Activate **Post views counter plugin**.

## Usage

In theme `functions.php`:

```php
add_theme_support('views', ['post_type' => 'post']);
```

## License

GPL-2.0-or-later

## Author

Aleksey Tikhomirov — [rwsite.ru](https://rwsite.ru)

---

## Русский

Счётчик просмотров записей. Включение: `add_theme_support('views');` в теме.
