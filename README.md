# custom-fields
Add Custom Field in Magento 2 Registration Form


Add custom fields or attribute on Magento 2 Registration form. This attribute also will show in add or edit customer form in Magento 2 Admin.

Installation process-

You can upload zip file on magento directory app\code and extract this zip folder

Module path like this app\code\Custom\Fields...

Then run below commands-

php bin/magento setup:upgrade

php bin/magetno setup:static-content:deploy

php bin/magento cache:flush
