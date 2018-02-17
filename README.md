Getting started with the auctioning app!

Why Feathers?
* For realtime Sockets.io and REST API’s
* Easily read and write from a Database (GET and POST)
* Quickly set up relations within a Database
* Easily creates authentication (hash passwords and JWT)


* Want more information?
    * https://docs.feathersjs.com/guides/basics/services.html

Installing Feathers JS
* npm install -g feathers-cli

Settting up our server
* In command line
    * feathers generate app
* Authentication - in command line
    * feathers generate authentication
        * Username/Password
        * Sequelize —> PostgreSQL
        * DB name - postgres://postgres:@localhost:5432/silent_auction
    * Create a database in PostgreSQL to match localhost
        * CREATE DATABASE silent_auction;
* Create services/tables using Service
    * feathers generate service

* Setting up hooks
    * feathers generate hook
