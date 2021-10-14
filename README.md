# Problem

We have two providers collect data from them in json files we need to read and make some filter
operations on them to get the result.

# Architecture
- Domain Driven Desing
- Service Oriented Architecure

# Design patterns used
- Repository
- Helper
- Service Provider
- Value object
- etc...

# Tools
- Lumen
- Doctrine ORM with yml mapping
- MySQL database

# Setup 
- create your .env file

- install dependencies
`composer install `

- create database tables
`cd Application/Src`
`php artisan doctrine:schema:update --force`

- run the project
`php -S localhost:8001 -t public`

# To do list
- unit testing
- seeds
