A web-based CRUD (Create, Read, Update, Delete) application developed with Laravel 12, PHP, MySQL, and Bootstrap. The application includes user authentication and different access levels for administrators and regular users.

Project Description

This project is a Laravel 12 application designed to manage records through a simple and user-friendly interface.

The application allows users to register and log in, while administrators have additional permissions to manage application data.

Features

will implement user registration (Sign Up)
Iwill implement user login (Log In)
will handle user authentication
will set up admin profile
will set up user profile
will support CRUD operations:
will create records
will read or view records
will update records
will delete records
will add a date of birth field that requires users to be 18 or older
will use a MySQL database}
will build an interface using Bootstrap
will use Laravel Blade templates
will add form validation
will run database migrations

Technologies Used
Laravel 12
PHP
MySQL
Bootstrap
HTML5
CSS3
JavaScript
Blade
Composer
Node.js / NPM
XAMPP


Project Structure

The main Laravel folders used in this project include:

app/
├── Http/
│   └── Controllers/
├── Models/

database/
├── migrations/
└── seeders/

resources/
├── css/
├── js/
└── views/

routes/
└── web.php
.env
composer.json
package.json
Important folders

app/Models/
Contains the application's Eloquent models.

app/Http/Controllers/
Contains the controllers responsible for application logic.

database/migrations/
Contains the instructions used to create and modify database tables.

resources/views/
Contains the Blade pages used by the application.

resources/css/
Contains the application's custom CSS files.

routes/web.php
Contains the application's web routes.

The application supports authentication with different user profiles:

Administrator

Administrators can have additional permissions to manage application records, including creating, viewing, updating, and deleting information.

Regular User

Regular users can access the functionality assigned to their profile and manage their own permitted information.
