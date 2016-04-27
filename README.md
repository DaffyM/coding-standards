## About
This project provides common coding standards for new ShopSys projects.
Project includes following tools:
* [PHP-CS-Fixer] (https://github.com/FriendsOfPHP/PHP-CS-Fixer)
* [PHP_CodeSniffer] (https://github.com/squizlabs/PHP_CodeSniffer)
* [PHPMD] (https://github.com/phpmd/phpmd)
* [PHP-Parallel-Lint] (https://github.com/JakubOnderka/PHP-Parallel-Lint)

## Usage examples
For further information see official documentation of particular project.
### PHP-CS-Fixer
```
vendor/bin/php-cs-fixer fix /path/to/project --config-file=vendor/shopsys/coding-standards/build/phpcs-fixer.php_cs
```
### PHP_CodeSniffer
```
vendor/bin/phpcs /path/to/project --standard=vendor/shopsys/coding-standards/rulesetCS.xml
```
### PHPMD
```
vendor/bin/phpmd /path/to/project text vendor/shopsys/coding-standards/rulesetMD.xml
```
### PHP-Parallel-Lint
```
vendor/bin/parallel-lint /path/to/project
```