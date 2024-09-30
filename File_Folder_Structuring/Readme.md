# File & Folder Structure In Laravel 🤞
## Where should we right our:
* Html
* Model
* Controller
* Routing
* File Store
* Config
* Database

Important info about `app/` directory is basically core code of Your application like `Model Controller & Middleware`.

In `app/console/kernel.php file` is where you can write custom cmd.

In `app/Exceptions/Handler.php file` is is basically use to write exceptions.

Even at the fresher/beginners level we don't work with these folders.

In `app/Http/Controllers folder` , `app/Http/Middleware folder` &  `Kernel.php` is very important even at the fresher/beginners level  basically in the controllers. We just write our controllers that simply means it just make interface between database and our html.

Then middleware it will just filter out the request like authentications, encryption kind of things like sometime redirection.

Then Kernel in the old middleware are registered in the kernel.

Then `app/Models folder` here we put those files that are related to database connection like models like `User.php file` will connect our database with the users table.

Then `app/Providers folder` this folder is still not used by freshers/beginners but here we just write the authentication services & routing services and all that kind of stuff. But sometime we just add here mannual and custom services also.

In `app/bootstrap folder` that is where only one main file and that is `app.js` and we will never make change in this file and this will just load our application in the browser Or you can say that this file is responsible for bootstrapping of our application.

In `app/bootstrap/cache folder` this folder will take the cache when we can just use some files you can see some code for the cache that will just provided here & when using our project the cache will automatically fill up here.

`app/config folder` this folder is very much useful for the fresher/beginners b/c we can do any kind of configuration here like database configuration imp for freshers session configuration email configuration kind of things .
