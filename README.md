[![Travis](https://img.shields.io/travis/Webysther/composer-meta-qa.svg?style=flat-square&maxAge=3600)](https://travis-ci.org/Webysther/composer-meta-qa)
[![Travis](https://img.shields.io/badge/HHVM-tested-orange.svg?style=flat-square&maxAge=3600)](https://travis-ci.org/Webysther/composer-meta-qa)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.3-8892BF.svg?style=flat-square&maxAge=3600)](https://php.net/)
[![Packagist](https://img.shields.io/packagist/v/webysther/composer-meta-qa.svg?style=flat-square&maxAge=3600)](https://packagist.org/packages/webysther/composer-meta-qa)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square&maxAge=3600)](https://raw.githubusercontent.com/Webysther/composer-meta-qa/master/LICENSE)

PHP Quality Assurance Tools
==========

This is a composer meta package for installing PHP Quality Assurance Tools with only one dependency, based on [h4cc/phpqatools](https://github.com/h4cc/phpqatools).

Included in this package (based on [phpqatools](http://phpqatools.org/)) are:

- [PHPUnit](https://github.com/sebastianbergmann/phpunit): Testing Framework
- [PHPCOV](https://github.com/sebastianbergmann/phpcov): CLI frontend for the [PHP_CodeCoverage](https://github.com/sebastianbergmann/php-code-coverage)
- [Paratest](https://github.com/brianium/paratest): Parallel testing for PHPUnit
- [DbUnit](https://github.com/sebastianbergmann/dbunit): Puts your database into a known state between test runs
- [PHPLOC](https://github.com/sebastianbergmann/phploc): A tool for quickly measuring the size of a PHP project
- [PHPCPD](https://github.com/sebastianbergmann/phpcpd): Copy/Paste Detector
- [PHP_Depend](https://github.com/pdepend/pdepend): Quality of your design in the terms of extensibility, reusability and maintainability
- [PHPMD](https://github.com/phpmd/phpmd): User friendly frontend application for the raw metrics stream measured by PHP Depend
- [PhpMetrics](https://github.com/phpmetrics/PhpMetrics): Static analysis tool, gives metrics about PHP project and classes
- [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer): Detects violations of a defined set of coding standards

Plus: 

- [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer): A tool to automatically fix coding standards issues
- [Security-Checker](https://github.com/sensiolabs/security-checker): Checks if your application uses dependencies with known security vulnerabilities
- [Behat](https://github.com/Behat/Behat): BDD (Behavior Driven Development) framework
- [Mockery](https://github.com/padraic/mockery): Simple yet flexible PHP mock object framework
- [Faker](https://github.com/fzaninotto/Faker): Generates fake data for you

Suggest install:

- [Prestissimo](https://github.com/hirak/prestissimo): Composer parallel install plugin

# Usage

The installed tools are available in vendor/bin/ and can be started like this:

```bash
php vendor/bin/phpmd
```

# Installation

To use this package, add it as as "dev" dependency with this command:

```bash
composer require webysther/composer-meta-qa --dev
```

Or modify your composer.json as followed:

```json
require-dev: {
  "webysther/composer-meta-qa": "@stable"
}
```
