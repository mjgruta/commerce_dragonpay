Commerce-Dragonpay
==================
INTRODUCTION
------------
This module let's you easily use DragonPay as a Payment Gateway with your
Drupal Commerce website.


REQUIREMENTS
------------
This module requires the following modules:
 * Commerce (https://drupal.org/project/commerce)
 * Commerce UI (https://drupal.org/project/commerce)
 * Commerce Payment (https://drupal.org/project/commerce)
 * Commerce Order (https://drupal.org/project/commerce)


INSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.
 * Make sure also to enable Commerce Payment UI to see the configuration.


CONFIGURATION
-------------
 1. Go to Store -> Configuration -> Payment Methods
 '?q=/admin/commerce/config/payment-methods' and edit Dragonpay.

 2. On the Action, look for "Enable payment method: Dragonpay" and click edit
 and Fill up the following information: Merchant ID and Secret Key/Password,
 then select the server you want. Click Save and you will now go back to
 "Dragonpay" rules.

 3. Click "Settings" to expand and check the checkbox for "Active" and click
 Save to enable this payment gateway.


MAINTAINERS
-----------
Current maintainers:
  * Mark Jayson Gruta (mjgruta) - https://www.drupal.org/user/1121748
