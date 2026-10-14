# HTTP Emitter Interface

A PHP interface for emitting PSR-7 HTTP responses.

## Requirements
PHP 8.0 or later

## Installation

Install the package using Composer:

`composer require sabroan/http-emitter-interface`

## Interface
```php
<?php

namespace Sabroan\Http\Emitter;

use Psr\Http\Message\ResponseInterface;

interface EmitterInterface
{
    public function emit(ResponseInterface $response): bool;
}
```

## License

This package is released under the MIT License. See the LICENSE file for details.