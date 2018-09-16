# TTL utils for @reactphp/cache implementors

[![Build Status](https://travis-ci.org/WyriHaximus/reactphp-cache-ttl-utils.svg?branch=master)](https://travis-ci.org/WyriHaximus/reactphp-cache-ttl-utils)
[![Latest Stable Version](https://poser.pugx.org/WyriHaximus/react-cache-ttl-utils/v/stable.png)](https://packagist.org/packages/WyriHaximus/react-cache-ttl-utils)
[![Total Downloads](https://poser.pugx.org/WyriHaximus/react-cache-ttl-utils/downloads.png)](https://packagist.org/packages/WyriHaximus/react-cache-ttl-utils)
[![Code Coverage](https://scrutinizer-ci.com/g/WyriHaximus/reactphp-cache-ttl-utils/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/WyriHaximus/reactphp-cache-ttl-utils/?branch=master)
[![License](https://poser.pugx.org/WyriHaximus/react-cache-ttl-utils/license.png)](https://packagist.org/packages/WyriHaximus/react-cache-ttl-utils)
[![PHP 7 ready](http://php7ready.timesplinter.ch/WyriHaximus/reactphp-http-middleware-clear-body/badge.svg)](https://travis-ci.org/WyriHaximus/reactphp-http-middleware-clear-body)

# Install

To install via [Composer](http://getcomposer.org/), use the command below, it will automatically detect the latest version and bind it with `^`.

```
composer require wyrihaximus/react-cache-ttl-utils
```

This middleware takes care of session handling. It uses [`react/cache`](https://reactphp.org/cache/) for storage or 
any cache handler implementing [`React\Cache\CacheInterface`](https://github.com/reactphp/react/wiki/Users#cache-implementations).

# License

The MIT License (MIT)

Copyright (c) 2018 Cees-Jan Kiewiet

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
