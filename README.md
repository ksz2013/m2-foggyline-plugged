# m2-foggyline-plugged

### Installation

```sh
$ composer config repositories.koncz-m2-foggyline-plugged git https://github.com/ksz2013/m2-foggyline-plugged.git
$ composer require koncz/m2-foggyline-plugged:dev-master
```

Manually:

Copy the zip into app/code/Foggyline/Plugged directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable Foggyline_Plugged --clear-static-content
$ php bin/magento setup:upgrade
```