# Laravel Mailcamp PHP Library

PHP client library to use the Mailcamp API.
Any PR's to make this package more complete, are very welcome.

# Installation using Composer
Installing this Mailcamp client for PHP can be done through Composer.

`composer require voicecode/laravel-dusk-mailcamp`

# Usage
Before using this package, please get a username and API token from Mailcamp. 
API tokens can't be created in their demo environment, so you'll have to contact their support.

# Currently available functions

## Lists
- Get all available lists
- Get the details of a specific list

## Subscribers
- Create a new subscriber for a list
- Check if an email address is subscribed to a list
- Update the email address of a subscriber
- Delete a subscriber from a list

## Stats
- Get statistics

## Token
- Check if your credentials are valid.

# Examples
Examples can be found at `examples.php`
