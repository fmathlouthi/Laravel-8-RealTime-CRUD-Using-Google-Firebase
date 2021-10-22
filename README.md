<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
<p><a target="_blank" rel="noopener noreferrer" href="/"><img src="https://github.com/fmathlouthi/Laravel-8-RealTime-CRUD-Using-Google-Firebase/blob/master/Laravel%20RealTime%20CRUD%20Using%20Google%20Firebase%20-%20Google%20Chrome%202021-10-22%2016-19-02.gif" alt="Laravel + Vue.js" data-canonical-src="https://github.com/fmathlouthi/Laravel-8-RealTime-CRUD-Using-Google-Firebase/blob/master/Laravel%20RealTime%20CRUD%20Using%20Google%20Firebase%20-%20Google%20Chrome%202021-10-22%2016-19-02.gif" style="max-width: 100%;"></a></p>
## About project

Laravel real-time CRUD using Google Firebase.




## Step 1 : Create a Firebase Project

Let’s first create a firebase project and take firebase credentials. Go to
https://firebase.google.com/ and create a project.

## Step 2 : Create a Laravel Project

composer create-project --prefer-dist laravel/laravel laravelproject

## Step 3 : Register View Route

- Go to routes >> web.php and register this route:
- <?php

Route::view('customers', 'customers');


## Step 4 : Configure Firebase Setting

Now, we are configuring google firebase setting in our laravel application. so, open config/services.php file and set following configuration in this file.

## Step 5 : Add a Blade File

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Step 6 : Run and Test

-  run php artisan serve

- Now visit the route(http://localhost:8000/customers) to see the form. You can start testing by adding data.



The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
