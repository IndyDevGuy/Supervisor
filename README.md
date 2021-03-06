# Supervisor [![Build Status](https://secure.travis-ci.org/yzalis/Supervisor.png)](http://travis-ci.org/yzalis/Supervisor)

**Supervisor** is a library which helps you to manage your supervisor instance.

## Basic Usage
```php
<?php

// create a new Supervisor instance
$supervisor = new \Supervisor\Supervisor();
```

## Unit Tests

To run unit tests, you'll need cURL and a set of dependencies you can install using Composer:
```
curl -sS https://getcomposer.org/installer | php
php composer.phar install
```

Once installed, just launch the following command:
```
phpunit
```

You're done.

## Credits

* Benjamin Laugueux <benjamin@yzalis.com>
* IndyDevGuy <contact@indydevguy.com>
* [All contributors](https://github.com/IndyDevGuy/supervisor/contributors)

Thanks for providing a huge amount of data to run tests:
* [http://user-agent-string.info](http://user-agent-string.info)
* [http://www.useragentstring.com](http://www.useragentstring.com)

## License

Supervisor is released under the MIT License. See the bundled license.txt file for details.
