# Matomo ForceSSL Plugin

## Description

When you activate this plugin, it will automatically redirect all "http://" requests to "https://" in the Matomo UI and API.
It also makes sure that the generated tracking code will use HTTPS. This is especially useful if your tracking code is
 embedded into your website automatically, for example via the WP-Matomo (WP-Piwik) Wordpress plugin.

For security and privacy reasons you should always use Matomo over HTTPS (SSL).

Note: If SSL or HTTPS is not correctly configured on your server, activating this plugin may break your Matomo. In such 
a case you can disable this plugin again by removing the line `Plugins[] = ForceSSL` from the `config/config.ini.php` file. 
In the same file there may be also a line `force_ssl = 1`. If you find such an entry and your server is not configured properly,
 we recommend to remove this line from the config file.

Any questions, feature wishes or problems? [Get in touch with us](https://www.innocraft.com), we are happy to help.

### About InnoCraft

We at [InnoCraft](https://www.innocraft.com) are the creators of Matomo and know it better than anyone else. 
This means all plugins are perfectly integrated into Matomo and come with outstanding features and quality to grow 
your business. We help our clients get started, configure, monitor and make the most of their Matomo analytics service. 
We also offer unique analytics products and services that help grow your business and meet the needs of medium and large 
businesses alike.
