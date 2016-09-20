# WordPress Multisite Common Users

When a new user is added in one site, add it to all the network sites

## Installation

Install the WordPress mu-plugin:

1. Add the file wpg-multisite-share-users.php in your wp-content/mu-plugins directory
2. (Optional) If your max sites > 10000, add to your wp-config.php :

```php
// Add msu max sites
define('MSU_MAX_SITES', <NUMBER>);
```
