<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel practise
laravel v10.18.0 <br />
laravel-lang v3.1 <br />
element-plus v2.3.9 <br />
PHP v8.1<br />
MySQL v8<br />
Composer v2.5.8 <br />

## Installation
<code>
composer install<br />
php artisan breeze:install<br />
php artisan migrate<br />
yarn install<br />
yarn dev<br />
php artisan lang:publish<br />
php artisan lang:add zh_TW<br />
php artisan lang:update<br />
</code>

#### 使用 Docker + Laravel Sail
<code>
./vendor/bin/sail up -d <br />
./vendor/bin/sail down <br />
./vendor/bin/sail restart <br />
</code>

#### 連上其他主機的 MySQL
.env<br />
<code>
DB_CONNECTION=mysql<br />
DB_HOST=host.docker.internal<br />
DB_PORT=3306<br />
DB_DATABASE=laravel_app<br />
DB_USERNAME=root<br />
DB_PASSWORD=<br />
</code>

#### Prod 優化
<code>
php artisan optimize:clear<br />
composer install --optimize-autoloader --no-dev<br />
php artisan config:cache<br />
php artisan route:cache<br />
php artisan view:cache<br />
</code>