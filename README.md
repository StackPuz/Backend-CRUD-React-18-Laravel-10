# Boilerplate-CRUD-React-18-Laravel-10
Boilerplate CRUD Web App created with React 18 + Laravel 10 by [StackPuz](https://stackpuz.com).

## Demo
Checkout the live demo at https://demo-spa.stackpuz.com

## Features
- Fully Responsive Layout.
- Sorting, Filtering and Pagination on Data List.
- User Management, User Authentication and Authorization, User Profile, Reset Password.
- Input Mask and Date Picker for date and time input field with Form Validation.

![Responsive Layout](https://stackpuz.com/img/feature/responsive.gif)  
![Data List](https://stackpuz.com/img/feature/list.gif)  
![User Module](https://stackpuz.com/img/feature/user.png)  
![Input Mask and Date Picker](https://stackpuz.com/img/feature/date.gif)

## Minimum requirements
- Composer 2.2
- Node.js 14.18
- PHP 8.1
- MySQL 5.7

## Installation
1. Clone this repository. `git clone https://github.com/stackpuz/Boilerplate-CRUD-React-18-Laravel-10.git .`
2. Change directory to React project. `cd react`
3. Install the React dependencies. `npm install`
4. Change directory to Laravel project. `cd ../laravel_api`
5. Install the Laravel dependencies. `composer install`
6. Create the symbolic link. `php artisan storage:link`
7. Create a new database and run [/database.sql](/database.sql) script to create tables and import data.
8. Edit the database configuration in [/laravel_api/.env](/laravel_api/.env) file.
    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=testdb
    DB_USERNAME=root
    DB_PASSWORD=
    ```

## Run project

1. Run React project. `npm run dev`
2. Run Laravel project. `php artisan serve`
3. Navigate to `http://localhost:5173`
4. Login with user `admin` password `1234`

## Customization
To customize this project to use other Database Engines, CSS Frameworks, Icons, Input Mask, Date picker, Date format, Font and more. Please visit [stackpuz.com](https://stackpuz.com).

## License

[MIT](https://opensource.org/licenses/MIT)