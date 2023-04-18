# PHP Code Standards

A collection of fixers/sniffs to support PHP coding standards that haven't made their way into packages yet, bundled as a Composer package.

If/when they are made into official releases from the original authors, they should be deprecated here with an appropriate link to update to the official release.

Namespaces adhere as closely to the origin/author's naming conventions as possible.

## Requirements

* PHP >= 8.1
* [Composer](http://getcomposer.org/)

## Installation

This is released as a Composer package, to install run the following command:
```
composer require codedruids/php-coding-standards
```

## Current packages

* `LaravelPhpdocAlignmentFixer`
<br>PHPDoc space alignment fixer for conforming with [Laravel](https://laravel.com) coding standards.
<br>Origin: [laravel/pint](https://github.com/laravel/pint) (@nunomaduro)

## License

Unless otherwise noted by individual fixers/sniffs, this package is licensed under the MIT license - see the [LICENSE](LICENSE) file for details.
