## Magento 2 Slovak Language Pack

**Install Slovak pack**:

``` php
composer require aveadev/magento-2-slovak-language-pack:dev-main
php bin/magento setup:static-content:deploy sk_SK
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
