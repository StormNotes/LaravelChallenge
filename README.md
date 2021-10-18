Greetings. For this repo to work you need to create a small Database in any SQL system or application.

To connect to this database in the env. file look up for these lines Example:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=reactcrudinfocasas <------ the name of your DB
DB_USERNAME=root    <----------------- username of the DB
DB_PASSWORD=password  <-------------------- Chosen password for the DB

after this the connection is done properly, set a migration to this database via the terminal you do this by using the command 

"php artisan migrate"

Assuming you have set npm correctly.
 
be aware that i have incorporated a UI library for lavarel to use React directly in the JS folder. such views are the commonly use "react compontents". 

to install these libraries, you need to use these commands in order: 


---->  "composer require laravel/ui"
---->  "php artisan ui react"

After this it will ask you to run: npm install && npm run dev

Viola! now you can use "php artisan serve" to check out the challenge
