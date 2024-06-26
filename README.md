
# PHP MVC Laravel Projects Source
This repository contains two PHP and MySQL projects that have been refactored to implement the MVC (Model-View-Controller) design pattern use Laravel. The original projects are from [PHPGurukul](https://phpgurukul.com/) and are:

![rtbs-project-php-520x245](https://github.com/TrashPorter/TrashPorter/assets/92986198/e74e0cb7-5702-4594-9c27-a10c678e738e)


- [Restaurant Table Booking System using PHP and MySQL](https://phpgurukul.com/restaurant-table-booking-system-using-php-and-mysql/)

## Refactoring to MVC

Both projects have been refactored to follow the MVC design pattern. The refactored structure separates the code into:

- Models: Handling data and database interactions.
- Views: Managing the presentation layer.
- Controllers: Handling the application logic and user input.

## Getting Started

### Prerequisites

- XAMPP or any compatible local server environment.
- Web browser.
- Basic knowledge of PHP and MySQL.
- Composer
- Node.js

### Installation

1. Download and Install XAMPP:

   - Download XAMPP from the [official website](https://www.apachefriends.org/index.html).
   - Install XAMPP and start the Apache and MySQL modules from the XAMPP Control Panel.

2. Clone the Repository:

```bash copy
  https://github.com/irfnriza/Kelompok_6_8_Laravel.git
```

3. Import the Database:

   - Open phpMyAdmin by navigating to http://localhost/phpmyadmin/.
   - Create new databases named rtbs.

4. Install Composer
   - https://getcomposer.org/download/

### Running the Projects
Open terminal at directory you clone this project and run this following command:
#### Get in folder
```bash
  cd Restaurant-Table-Booking-System
```
#### Run composer Install
```bash
  composer install
```
#### Run npm install
```bash
  npm install
```
#### Copy file .env.example to .env
```bash
  cp .env.example .env
```
#### Activate key use command artisan
```bash
  php artisan key:generate
```
#### In file .env change database name and password    
```bash
  DB_DATABASE=rtbs
  DB_USERNAME=<username mysql>
  DB_PASSWORD=<password>
```

#### Migration    
```bash
  php artisan migrate:fresh --seed
```

#### Open terminal and run     
```bash
  php artisan serve
```
#### Open this on your browser:
```url
http://127.0.0.1:8000 
```
# Laravel Project Structure
- app/: 
    Contains the core code of the application, including:
    - Models: Located in app/Models/, these classes interact with the database.
    - Controllers: Located in app/Http/Controllers/, these classes handle the application logic and user input.
    - Middleware: Located in app/Http/Middleware/, these classes filter HTTP requests entering the application.
    - Console: Contains Artisan commands.
    - Exceptions: Handles application exceptions.
    - Providers: Service providers that configure and bind services into the service container.

- bootstrap/: 
    Contains the app.php file that initializes the framework.
    - cache/: Contains framework-generated files for performance optimization.

- config/: 
    Contains all of the configuration files for the application.

- database/: 
    Contains database-related files, including:
    - migrations/: Database migration files.
    - factories/: Factory classes for testing.
    - seeders/: Database seeders for populating the database.

- public/: 
    Contains publicly accessible files, including:
    - index.php: The entry point for all requests to the application.
    - assets/: CSS, JavaScript, and images.

- resources/: 
    Contains view files and raw assets, including:
    - views/: Blade templates for rendering the user interface.
    - lang/: Localization files.
    - js/: JavaScript files.
    - sass/: Sass files for CSS pre-processing.

- routes/: 
    Contains all route definitions for the application, organized by HTTP method and middleware.

- storage/: 
    Contains compiled Blade templates, file-based sessions, file caches, and other files generated by the application.
    - app/: Application-specific files.
    - framework/: Framework-generated files and caches.
    - logs/: Application log files.

- tests/: 
    Contains automated tests, including:
    - Feature: Tests for larger interactions within the application.
    - Unit: Tests for individual components of the application.

- vendor/: 
    Contains the Composer dependencies.

- .env: 
    Contains environment-specific configuration variables.

- artisan: 
    The Artisan CLI script for interacting with the Laravel framework from the command line.


# Contributors
| Nama        | NPM           | 
| ------------- |:-------------:|
| Nazwa Salsabila       | 2208107010010 |
| ⁠Berliani Utami       | 2208107010082 |
| Raihan Firyal          | 2208107010084 |
| Riska Haqiqa Situmorang      | 2208107010086 |
| Mizana Amaliya      | 240610302022150012 |
| Irfan Rizadi      | 2208107010082 |
| Al Mahfuzh Fadhlur Rohman      | 22081070100816 |
| Shidqi Rabbani      | 1908107010055 |
| Muhammad Teguh Aulia      | 2208107010082 |

## Acknowledgements

 - [PHPGurukul](https://phpgurukul.com/)
 - [Restaurant Table Booking System using PHP and MySQL](https://phpgurukul.com/restaurant-table-booking-system-using-php-and-mysql/)


## Tech Stack

**Client:** Laravel, Bootstrap

**Server:** Apache

