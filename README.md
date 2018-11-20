## Magento 2 Province Italiane
Module that implements italian regions for Magento 2.x from [Artera](https://www.artera.it/) team.

### 1. Install the module
We explain two different methods to install this module, we reccomend choosing composer.

##### Method #1. With Composer (recommended - is required Authentication)

**Install the module**
```
composer require artera/magento-2-province-italiane:dev-master
```

##### Method #2. Download and upload the module locally (not recommended)

**Download the module**
Download our module from this repository.

**Upload the module in your magento installation**
Create these subdirectories path in your magento root folder like **[Your_Magento_Root]**`/app/code/Artera/ProvinceItaliane/`
Unzip the module here.


### 2. Enable the module

##### Method #1. From Command Line (recommended)

```
php bin/magento module:enable Artera_ProvinceItaliane
php bin/magento setup:upgrade
```

##### Method #2. From Magento 2 admin panel (not recommended)

Here `System > Web Setup Wizard > Module Manager` search the module line, select action "Enable" and follow the steps form web interface. 

### 3. Flush the cache if required 

##### Method #1. From Command Line

```
php bin/magento cache:flush
```

##### Method #2. From Magento 2 admin panel

Here `System > Cache Management > Flush Magento Cache`



## License
[The OSL-3.0 License](http://opensource.org/licenses/OSL-3.0)
