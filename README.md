PHP Quality Assurance Tools [![Build Status](https://travis-ci.org/Webysther/composer-meta-qa.svg?branch=master)](https://travis-ci.org/Webysther/composer-meta-qa) [![License](https://poser.pugx.org/webysther/composer-meta-qa/license)](https://packagist.org/packages/webysther/composer-meta-qa)
==========

This is a composer meta package for installing PHP Quality Assurance Tools with only one dependency, based on [h4cc/phpqatools](https://github.com/h4cc/phpqatools).

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
