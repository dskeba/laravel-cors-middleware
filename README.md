# laravel-cors-middleware

Simple middleware to allow CORS on Laravel 5

## Installation

(1) Copy Cors.php into /App/Http/Middleware directory.

(2) Add middleware to Kernel.php file:

'cors' => \App\Http\Middleware\Cors::class,

(3) Include middleware in your route(s):

Route::group(['middleware' => 'cors'], function () {
	//
});

## About the Author

laravel-cors-middleware is created and maintained by [Derek Skeba](http://derekskeba.com)