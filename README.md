auth-token
==========

Laravel token based authentication package

## Setup
- Add this to your Autoloaded Service Providers array in config/app.php
```php
Dwolf555\AuthToken\AuthTokenServiceProvider
```
- Run migrations using artisan
```
php artisan migrate --package="dwolf555/auth-token"
```
- Add a user using your own methods
- Add before filter 'auth-token' to your routes/controllers
- Login via POST /login with fields email/password or username/password