magento2-Inchoo_Stripe
======================

Gridthumbs Magento2 extension

Install
=======

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer config repositories.inchoostripe git https://github.com/trancosmos/gridthumbs.git
    composer require trancosmos/gridthumbs:dev-master
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
    php bin/magento setup:upgrade
    ```

