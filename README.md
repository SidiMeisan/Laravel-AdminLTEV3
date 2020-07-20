## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is to create an Admin LTE page using laravel as back-end programming
	
## Setup
To run this project, install it locally using this code:

```
$ git clone linktogithubrepo.com/projectName
$ cd projectName
```
You can change the last word (“tutorial” in this example) to be the name of the working branch you prefer. This is going to checkout the start tag and put it on a fresh new branch with the name you provide here. This allows you to work without ruining the final code in your project (you can always move over to the master branch for the final).

Create an empty database for your project using the database tools you prefer. In our example we created a database called “test”. Just create an empty database.
```
$ composer install
$ npm install
$ cp .env.example .env
$ php artisan key:generate
```
In the .env file fill in the DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD options to match the credentials of the database you just created. This will allow us to run migrations and seed the database in the next step.
```
$ php artisan migrate
$ php artisan db:seed
```