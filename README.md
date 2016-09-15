# WordPress Multisite Share Users

When a new user is added in one site, add it to all the network sites

## Installation

You can install this plugin via the command-line or the WordPress admin panel.

## via Command-line

1. Download the [latest zip](https://github.com/wp-globalis-tools/wpg-multisite-share-users/archive/master.zip) of this repo.
2. Add the folder in your plugins directory (wp-content/plugins)
3. Activate the plugin via [wp-cli](http://wp-cli.org/commands/plugin/activate/).

```sh
wp plugin activate wpg-multisite-share-users

## via WordPress Admin Panel

1. Download the [latest zip](https://github.com/wp-globalis-tools/wpg-multisite-share-users/archive/master.zip) of this repo.
2. In your WordPress admin panel, navigate to Plugins->Add New
3. Click Upload Plugin
4. Upload the zip file that you downloaded.

## Configuration

Define MSU_MAX_SITES in your config file :
