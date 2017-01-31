# CodeIgniter 2 + PHPUnit

- [Project Summary](#summary)
- [Installation](#installation)
- [License](#license)

<a name="summary"></a>
## Project Summary

This package combines [CodeIgniter 2](https://github.com/rogeriopradoj/codeigniter) and [Fernando Piancastelli's modifications](https://github.com/fmalk/codeigniter-phpunit/tree/2.x) to get CI to play nice with PHPUnit.

<a name="installation"></a>
## Installation

- Add the following to your project's `composer.json` file:

```json
"repositories" : [
    {
        "type" : "vcs",
        "url" : "https://github.com/rethink-group/codeigniter-2-phpunit.git"
    }
],
```
- Run `composer require rethink-group/codeigniter-phpunit-2.x` to install the package.

- Modify `httpdocs/index.php` by changing the following line:

```php
$system_path = 'system';
```

to

```php
$system_path = 'vendor/rethink-group/codeigniter-2-phpunit/system';
```

<a name="license"></a>
## License
See [license.txt](license.txt) for CodeIgniter's license.
