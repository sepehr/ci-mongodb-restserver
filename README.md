# CodeIgniter MongoDB REST Server
A fully RESTful server implementation for CodeIgniter with optional MongoDB backend.

This is just a minor fork of Phil Sturgeon's [CodeIgniter REST Server](https://github.com/philsturgeon/codeigniter-restserver) library to add support for MongoDB to be used with API keys, logs and limits. All the credits goes to Phil Sturgeon, again, it's just a minor fork.

## Requirements
* PHP 5.2+
* CodeIgniter 2.1.0+
* [CodeIgniter MongoDB Active Record](https://github.com/alexbilbie/codeigniter-mongodb-library/tree/v2) library (v2)

## Installation

* Properly setup MongoDB config directives in both `application/config/mongodb.php` and `application/config/rest.php`
* And you're done!