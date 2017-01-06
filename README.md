# Piwik ForceSSL Plugin

## Description

When you activate this plugin, it will automatically redirect all "http://" requests to "https://" in the Piwik UI and API.
For security and privacy reasons you should always use Piwik over HTTPS (SSL).

Note: If SSL or HTTPS is not correctly configured on your server, activating this plugin may break your Piwik. In such 
a case you can disable this plugin again by removing the line `Plugins[] = ForceSSL` from the `config/config.ini.php` file. 
In the same file there may be also a line `force_ssl = 1`. If you find such an entry and your server is not configured properly,
 we recommend to remove this line from the config file.

Any questions, feature wishes or problems? [Get in touch with us](https://www.innocraft.com), we are happy to help.