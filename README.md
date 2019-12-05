# Creating a new Package

## Create new Boilerplate
- visit [https://laravelpackageboilerplate.com//](https://laravelpackageboilerplate.com/#/)

## Add The Following to the boilerplate
- helpers.php
- phpcs.xml
- .vscode

## Modify composer.json that fits your needs
- add laravel package tools to use pkg command
```json
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/Jhnbrn90/laravel-package-tools"
        }
    ],
    "require": {
        "phpunit/phpunit": "^8.4",
        "illuminate/console": "^6.0",
        "illuminate/http": "^6.0",
        "illuminate/support": "^6.0"
    },
    "require-dev": {
        "beyondcode/laravel-package-tools": "dev-feature/add-support-for-laravel-6",
        "squizlabs/php_codesniffer": "^3.4",
        "nadar/php-composer-reader": "^1.2",
        "jackiedo/dotenv-editor": "^1.0"
    },
```
