# Laravel Trait Generator [![Build Status](https://travis-ci.com/musamamasood/trait-generator.svg?branch=master)](https://travis-ci.com/musamamasood/trait-generator)
Laravel Generator For Creating New Traits

## Installation

Install using composer
```
composer require cedextech/trait-generator --dev
```

Add the service provider, open `config/app.php`, and add a new item to the providers array.

```
Cedextech\TraitGenerator\ServiceProvider::class,
```

That's it! You're all set to go. Run the `php artisan` command from the Terminal to see the new `make:trait` command.

## Usage

```
php artisan make:trait UserTrait
```
