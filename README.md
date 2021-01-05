
## Run project
### Step1: Run command to install library:

```$ composer install```

### Step2: Run command to create .env file:

```$ cp .env.example .env```

### Step3: Run command to generate key:

```$ php artisan key:generate```

### Step4: Make database:

Go to xampp in local make database.

Set up database in .env file

Run script to make table in database 

```$ php artisan migrate --seed```
### Step5: Add database from csv file:
```$ php artisan db:seed```
or
```$ php artisan db:seed --class <nameTableSeeder```
eg
```$ php artisan db:seed --class UserTableSeeder```
```$ php artisan db:seed --class AdminTableSeeder```
```$ php artisan db:seed --class ProductTableSeeder```
```$ php artisan db:seed --class BrandTableSeeder```



### Step6: Run command to start project

```$ php artisan serve```

