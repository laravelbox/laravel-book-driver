<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<style>
    .code{
        color:grey;
        font-style:italics;
        background:lightyellow;
        border-radius: 5px;
        padding: 5px;
    }
</style>

## How to build Laravel 10 CRUD Application with Bootstrap 5 and mySQL

Please follow the steps to create a new Laravel project and install Bootstrap in Laravel Project:

## Install Laravel Project
<p>Run the command to install Laravel project.</p>
<pre>composer create-project laravel/laravel laravel-book-driver</pre>
<pre>composer create-project --prefer-dist laravel/laravel laravel-book-driver</pre>
<pre>cd laravel-book-driver</pre>

## Set up Database Connection
<p>Open .env file in the Laravel project.</p>
.env without Docker container
<pre>
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_book_driver
DB_USERNAME=root
DB_PASSWORD=secretpassword
</pre>
.env with Docker container
<pre>
DB_CONNECTION=mysql
DB_HOST=db
DB_PORT=3306
DB_DATABASE=laravel_book_driver
DB_USERNAME=root
DB_PASSWORD=secretpassword
</pre>

## Install Laravel/UI
<p>Run the command to install Laravel/UI.</p>
<pre>composer require laravel/ui</pre>

## Install Bootstrap in Laravel
<p>Run the command to install bootstrap in the Laravel project.</p>
<pre>php artisan ui bootstrap</pre>

## Install Bootstrap Auth Scaffolding
<p>Run the command to install auth scaffoldings with Bootstrap in the Laravel project.</p>
<pre>php artisan ui bootstrap --auth</pre>

## Install Bootstrap Packages
<p>Run the command to install Bootstrap packages in the Laravel project.</p>
<pre>npm install</pre>

## Compile Assets
<p>Run the command to compile assets in the Laravel project.</p>
For development
<pre>npm run dev</pre>
For production
<pre>npm run production</pre>
To automate sass and javascript changes
<pre>npm run watch</pre>
To build assets to be ready to deploy
<pre>npm run build</pre>