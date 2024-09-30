# Installation Of Laravel
**Install Laravel 8**

There are two step 
- **Laravel installer**
You may create new Laravel projects by globally installing the Laravel installer via Composer. The Laravel installer allows you to select your preferred testing framework, database, and starter kit when creating new applications:
```bash
composer global require laravel/installer
 
laravel new example-app
```
- **Composer Create-Project**
* In my case I'm using `composer create-project laravel/laravel example-app` cmd b/c it insatll all dependencies and project name at a time.
* It's pretty fast n Quick. Then run cmd 
```bash 
laravel 
```
  and check the status of new project
* Then run cmd 
```bash 
ls 
``` 
to check the if the folder is exist or not if yes then go head by running the cmd 
```bash 
cd laravel-blog-app
``` 
* After you have installed PHP and Composer
* While setting up new Project of laravel at the end you should run the cmd provided below
```bash
 php artisan serve
```
## Now You're Good to Go You're Server Is live Now 🎉😊

## Key Concepts

- **composer.json**: Yeh file aapke project ki dependencies aur unki versions ko define karti hai. Isme aapko libraries ka naam aur required version specify karna hota hai.

- **vendor directory**: Jab aap `composer install` command run karte hain, toh Composer required packages ko download karke `vendor` directory mein store karta hai.

- **Autoloading**: Composer autoloading feature provide karta hai jo classes ko automatically load karne mein madad karta hai. Isse aapko `require` statements likhne ki zaroorat nahi hoti.

## Basic Commands

- **Install Dependencies**: 
  ```bash
  composer install
- **Dependencies to update in latest versions**: 
```bash
composer update
```
Yeh command installed packages ko latest versions mein update karta hai.

- **Check Composer setup**: 

By running the command 
  ```bash
  composer 
```
it will tell you if the composer works properly or not