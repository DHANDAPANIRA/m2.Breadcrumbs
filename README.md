# Magento2 Breadcrumbs

Extension add breadcrumbs to pages in Magento 2 that by default do not have breadcrumbs. 

[![Total Downloads](https://poser.pugx.org/faonni/module-breadcrumbs/downloads)](https://packagist.org/packages/faonni/module-breadcrumbs)
[![Latest Stable Version](https://poser.pugx.org/faonni/module-breadcrumbs/v/stable)](https://packagist.org/packages/faonni/module-breadcrumbs)	

<img alt="Magento2 Breadcrumbs" src="https://karliuka.github.io/m2/breadcrumbs/account.png" style="width:100%"/>

## Compatibility

Magento CE(EE) 2.0.x, 2.1.x, 2.2.x

## Install

#### Install via Composer (recommend)

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer require faonni/module-breadcrumbs
    ```
   Wait while dependencies are updated.
   
#### Manual Installation
   
1. Create a folder {Magento root}/app/code/Faonni/Breadcrumbs

2. Download the corresponding [latest version](https://github.com/karliuka/m2.Breadcrumbs/releases)

3. Copy the unzip content to the folder ({Magento root}/app/code/Faonni/Breadcrumbs)

### Completion of installation

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
	php bin/magento setup:upgrade
	php bin/magento setup:di:compile
	php bin/magento setup:static-content:deploy  (optional)

### Configuration

In the Magento Admin Panel go to *Content > Configuration > {Your Theme} > Breadcrumbs*.

<img alt="Magento2 Breadcrumbs" src="https://karliuka.github.io/m2/breadcrumbs/config.png" style="width:100%"/>

## Uninstall
This works only with modules defined as Composer packages.

#### Remove database data

1. Go to Magento2 root folder

2. Enter following commands to remove database data:

    ```bash
    php bin/magento module:uninstall -r Faonni_Breadcrumbs
  
#### Remove Extension
    
1. Go to Magento2 root folder

2. Enter following commands to remove:

    ```bash
    composer remove faonni/module-breadcrumbs
    ```

### Completion of uninstall

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
	php bin/magento setup:upgrade
	php bin/magento setup:di:compile
	php bin/magento setup:static-content:deploy  (optional)
    
* [Breadcrumbs from Magento](https://github.com/karliuka/m1.Breadcrumbs)
