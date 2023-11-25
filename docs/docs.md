# Magento Adobe Docs

<https://experienceleague.adobe.com/docs/commerce-admin/user-guides/home.html>

## Integrate payments with stripe

<https://stripe.com/docs/connectors/adobe-commerce/install>

<https://stripe.com/docs/payments/finalize-payments-on-the-server>

## PHP

## Install on MacOS

    brew install php 

- Message shown after installation

To enable PHP in Apache add the following to httpd.conf and restart Apache:
    LoadModule php_module /opt/homebrew/opt/php/lib/httpd/modules/libphp.so

    <FilesMatch \.php$>
        SetHandler application/x-httpd-php
    </FilesMatch>

Finally, check DirectoryIndex includes index.php
    DirectoryIndex index.php index.html

The php.ini and php-fpm.ini file can be found in:
    /opt/homebrew/etc/php/8.2/

To start php now and restart at login:
  brew services start php
Or, if you don't want/need a background service you can just run:
  /opt/homebrew/opt/php/sbin/php-fpm --nodaemonize

- Check successful installation

    php -v

### Mamp

### Packagist

Packages for PHP

<https://packagist.org>

## XAMP

<https://www.apachefriends.org/>

## MAMP

- Docs
<https://www.mamp.info/en/downloads/>

<https://documentation.mamp.info/en/MAMP-Mac/Installation/index.html>

## MariaDB on MacOS

<https://mariadb.com/resources/blog/installing-mariadb-10-1-16-on-mac-os-x-with-homebrew/#:~:text=Installing%20MariaDB%20Server%20on%20Mac%20OS%20X%20with,...%208%208.%20Start%20MariaDB%20...%20More%20items>

## Apache server

    brew install httpd

    brew services start httpd
    
    vi /opt/homebrew/etc/httpd/httpd.conf

<https://www.youtube.com/watch?v=xyHlJLjzf1w>

<https://httpd.apache.org/download.cgi>

<https://www.git-tower.com/blog/apache-on-macos/>

<https://tecadmin.net/install-apache-macos-homebrew/#:~:text=1%20Install%20Apache%20on%20macOS.%20Remove%20built-in%20Apache,for%20the%20testing.%204%20Manage%20Apache%20Service>

<https://discussions.apple.com/docs/DOC-250004361>

<https://tomcat.apache.org/>
