## Laravel 5.1 example##

**Laravel 5.1 news Website / Blog example** is a simple application for the News Website or Blog.

### Installation ###

* `git clone https://github.com/smile-zhao/Laravel5.1_Example.git ProjectName`
* `cd ProjectName`
* `composer install`
* `php artisan key:generate`
* Create a database and change in *`.env.example`*, 
* Rename `.env.example` to `.env` (`mv .env.example .env`)
* `php artisan migrate --seed` create and seed the database
* `php artisan serve` to start the app on http://localhost:8000/
* All routes are informed in the file `App/Http/routes.php`

### Include ###

* [jQuery](https://jquery.com/m)	
* [Bootstrap](http://getbootstrap.com) for CSS and jQuery plugins
* [DataTables.js](https://www.datatables.net/) table plug-in for jQuery
* [selectize.js](http://selectize.github.io/selectize.js/) for custom Select UI Control
* [pickadate.js](http://amsul.ca/pickadate.js/) for date and time input picker
* [Filemanager](https://github.com/simogeo/Filemanager) the easy file manager
	
### Features ###

* Admin & Author home page
* Authentication (registration, login, logout)
* Users roles : Admin, Author
* Admin : Audited mechanism( every article need be reviewed before publishing), Tag(edit, delete, create)
* Author : Article (show, edit, delete, create)
* Tags on articles

### Packages included ###

* [michelf/php-markdown](https://github.com/michelf/php-markdown) parser for Markdown and Markdown Extra
* [michelf/php-smartypants](https://github.com/michelf/php-smartypants) web typography prettifyier tool for web writers
* [mewebstudio/Purifier](https://github.com/mewebstudio/Purifier) HTML Purifier for Laravel 5

### Seeds ###
For testing the application, the database is been seeded with users:

*	name:	admin,		password:	admin
* 	name:	author, 	password:author