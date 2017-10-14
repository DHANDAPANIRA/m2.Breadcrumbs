# Magento2 Breadcrumbs

Extension add breadcrumbs to pages in Magento 2 that by default do not have breadcrumbs. 

<img alt="Magento2 Breadcrumbs" src="https://karliuka.github.io/m2/breadcrumbs/account.png" style="width:100%"/>

## Install with Composer as you go

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer require faonni/module-breadcrumbs
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
	php bin/magento setup:upgrade
	php bin/magento setup:static-content:deploy
    ```
 4. Go to Configuration > Design > Breadcrumbs and set Enabled to Yes
    
* [Breadcrumbs from Magento](https://github.com/karliuka/m1.Breadcrumbs)
