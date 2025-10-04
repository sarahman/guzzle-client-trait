# Guzzle Client Trait

[![Latest Version on Packagist](https://img.shields.io/packagist/v/sarahman/guzzle-client-trait.svg?style=flat-square)](https://packagist.org/packages/sarahman/guzzle-client-trait)
[![Build Status](https://img.shields.io/travis/com/sarahman/guzzle-client-trait/master.svg?style=flat-square)](https://travis-ci.org/sarahman/guzzle-client-trait)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/sarahman/guzzle-client-trait/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/sarahman/guzzle-client-trait/?branch=master)
[![StyleCI](https://styleci.io/repos/1069555720/shield)](https://styleci.io/repos/1069555720)
[![Total Downloads](https://img.shields.io/packagist/dt/sarahman/guzzle-client-trait.svg?style=flat-square)](https://packagist.org/packages/sarahman/guzzle-client-trait)
[![License](http://poser.pugx.org/sarahman/guzzle-client-trait/license)](https://packagist.org/packages/sarahman/guzzle-client-trait)
[![PHP Version Require](http://poser.pugx.org/sarahman/guzzle-client-trait/require/php)](https://packagist.org/packages/sarahman/guzzle-client-trait)

This PHP library is intended to handle guzzle client creation, its API calls &amp; their corresponding responses and can be used in any php project.

## Installation

- Step 1: You can install the package via composer:

``` bash
composer require sarahman/guzzle-client-trait
```

- Step 2: for the regular php projects, we might directly add these following codes:

```php

require "vendor/autoload.php";

use Sarahman\Traits\Guzzles;

class SampleAPIClient
{
    use Guzzles;

    ...
}
```

## Contribution

Feel free to contribute in this library. Please make your changes and send us [pull requests](https://github.com/sarahman/guzzle-client-trait/pulls).

## Security Issues

If you discover any security related issues, please feel free to create an issue in the [issue tracker](https://github.com/guzzle-client-trait/issues) or write us at [aabid048@gmail.com](mailto:aabid048@gmail.com).

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
