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

### Http Controllers `app/Controllers folder`
  

### Http Middleware `app/Http/Middleware folder`
  

### Kernel `app/Http/Kernel.php file`
  
In `app/Http/Controllers folder` , `app/Http/Middleware folder` &  `Kernel.php` is very important even at the fresher/beginners level  basically in the controllers. We just write our controllers that simply means it just make interface between database and our html.

Then middleware it will just filter out the request like authentications, encryption kind of things like sometime redirection.

Then Kernel in the old middleware are registered in the kernel.

### Models `app/Models folder`
  
Then `app/Models folder` here we put those files that are related to database connection like models like `User.php file` will connect our database with the users table.

### Providers `app/Providers folder`
Then `app/Providers folder` this folder is still not used by freshers/beginners but here we just write the authentication services & routing services and all that kind of stuff. But sometime we just add here mannual and custom services also.

### Bootstrap folder

In `app/bootstrap folder` that is where only one main file and that is `app.js` and we will never make change in this file and this will just load our application in the browser Or you can say that this file is responsible for bootstrapping of our application.


### Bootstrap Cache `bootstrap/cache folder`
In `bootstrap/cache folder` this folder will take the cache when we can just use some files you can see some code for the cache that will just provided here & when using our project the cache will automatically fill up here.

### Config `config folder` 

This `config folder` is very much useful for the fresher/beginners b/c we can do any kind of configuration here like database configuration imp for freshers session configuration email configuration kind of things .

### Database folder

This `database folder` is again useful for the fresher. And here we write the Factories, Migration and Seedings.
* Factories is use for database testing. In this you can generate fake data for models, which is useful in testing and seeding.
* Migration means migrate the table from one database to another database when we are using the database by many developers then one database want to share the data with the another developer then we use the migration for that purpose.
* Seedings means putting the fake data.

### Public folder `public folder` 

There is only one important file which is `index.php` `public/index.php file` and this is the first file that is load from our application. OR the first file which is loaded by the Browser.

### Resources `resources folder`

File of this folder is where we can put like public files of `Css`, `Javasript` and sometimes `local` files also and in the `view` we basically put our complete Html right here. Even we can make the nested folder also.

### Routes `routes folder`

This `routes folder` is responsible for making the route URL for the web as well as the api.

### Storage `storage folder`

This `storage folder` is for storing the files.

### Tests `tests folder`

This `tests folder` is where we write the unit test cases with the end to end the unit test the both kind of test cases.

### Vendor `vendor folder`

This `app/vendor folder` is basically where we have the dependency which is loaded by the package.json OR sometime custom  dependency also.
 
### Enviroment `.env file`

This `.env file` define our database credentials, all other credentials like radis & sometime other credentials like aws.
 
### Artisan `artisan file`

This `artisan file` is used for the command line.

### Package.json `Package.json file`

This `Composer.json file` is where all the old dependencies packages are mentioned here.

### Package.json `Package.json file`

This `package.json file` is not useful when we are creating apis but when we use any `front-end Framework` like React, Vue, Angular then this is a useful 

### PhpUnit.xml `phpUnit.xml file`

This `phpUnit.xml file` is useful for the right unit test cases.

### Readme `Readme.md file`

This `Readme.md file` is Where we can write the descripsion of the project.