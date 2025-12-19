# magento2-weltpixel-layered-navigation-lite

### Installation

Dependencies:
- magento2-weltpixel-backend (see https://github.com/Weltpixel/magento2-weltpixel-backend)

With composer:

```sh
$ composer config repositories.weltpixel-magento2-weltpixel-backend git https://github.com/Weltpixel/magento2-weltpixel-backend.git
$ composer require weltpixel/magento2-weltpixel-backend:dev-master

$ composer config repositories.weltpixel-magento2-weltpixel-layered-navigation-lite git https://github.com/Weltpixel/magento2-weltpixel-layered-navigation-lite.git
$ composer require weltpixel/magento2-weltpixel-layered-navigation-lite:dev-master
```
Manually:

Important: Ensure you also install the shared Backend module. If it's already installed, you can skip this. Details in the repo at https://github.com/Weltpixel/magento2-weltpixel-backend.


Copy the zip into the app/code/WeltPixel/LayeredNavigation directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable WeltPixel_LayeredNavigation --clear-static-content
$ php bin/magento setup:upgrade
```

### Documentation

For detailed documentation, please visit: https://github.com/Weltpixel/magento2-weltpixel-documentation/tree/master/Magento2/LayeredNavigation
