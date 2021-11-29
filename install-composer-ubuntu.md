
## install composer

## install need package
````
sudo apt install software-properties-common
sudo add-apt-repository ppa:ondrej/php
sudo apt install php7.3 php7.3-common php7.3-opcache php7.3-cli php7.3-gd php7.3-curl php7.3-mysql
````

## verify install 
````
php -v

Copy
PHP 7.3.1-1+ubuntu18.04.1+deb.sury.org+1 (cli) (built: Jan 13 2019 10:19:33) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.3.1, Copyright (c) 1998-2018 Zend Technologies
    with Zend OPcache v7.3.1-1+ubuntu18.04.1+deb.sury.org+1, Copyright (c) 1999-2018, by 
````

## download composer
````
curl -sS https://getcomposer.org/installer -o composer-setup.php
````
## install composer 
````
sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
````
