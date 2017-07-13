# Magento 2 Cloud show-case theme
**theme-frontend-vasiliy**

## Installation
1. add repository to the composer
```
"repositories": [
      {
        "type": "vcs",
        "url": "https://github.com/vasiliyseleznev/theme-frontend-vasiliy"
      }
    ],
```
2. add package to require section
```
"require": {
        "vasiliyseleznev/theme-frontend-vasiliy": "*",
        ...
```
3. run composer update
4. run bin/magento module:enable Magento_GraphQL
5. bin/magento setup:upgrade
6. bin/magento cache:clean
