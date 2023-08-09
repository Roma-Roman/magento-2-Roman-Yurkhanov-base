# RomanYurkhanov Base for Magento 2
#### RomanYurkhanov Base module for Magento 2. All RomanYurkhanov modules requires this module.

[![Latest Stable Version](http://poser.pugx.org/romanyurkhanov/module-base/v)](https://packagist.org/packages/romanyurkhanov/module-base)
[![Total Downloads](http://poser.pugx.org/romanyurkhanov/module-base/downloads)](https://packagist.org/packages/romanyurkhanov/module-base)

## Extension Screenshots
<img width="1792" alt="Screenshot 2023-08-09 at 15 46 04" src="https://github.com/Roma-Roman/magento-2-Roman-Yurkhanov-base/assets/14273213/ee89c1ee-53f0-4a00-bc51-99979061940d">
<img width="1792" alt="Screenshot 2023-08-09 at 15 46 45" src="https://github.com/Roma-Roman/magento-2-Roman-Yurkhanov-base/assets/14273213/f6758155-6c7d-4a40-9d4c-60417ef1cb98">


## How to install & upgrade RomanYurkhanov_Base

### 1. Install via composer (recommend)

I recommend you to install RomanYurkhanov_Base module via composer. It is easy to install, update and maintenance.

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require romanyurkhanov/module-base
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update romanyurkhanov/module-base
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way. 

- Download [the latest version here](https://github.com/Roma-Roman/magento-2-Roman-Yurkhanov-base/archive/main.zip)
- Extract `main.zip` file to `app/code/RomanYurkhanov/Base` ; You should create a folder path `app/code/RomanYurkhanov/Base` if not exist.
- Go to Magento root folder and run upgrade command line to install `RomanYurkhanov_Base`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
