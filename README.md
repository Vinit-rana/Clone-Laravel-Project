# Clone-Laravel-Project

How to clone Laravel Project!? 
- It's simple follow the following steps!  
1. Clone your project
2. Go to the folder application using cd command on your cmd or terminal
3. Run composer install on your cmd or terminal
4. Copy .env.example file to .env on the root folder. You can type copy .env.example .env if using command prompt Windows or cp .env.example .env if using terminal, Ubuntu
5. Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration.
6. Run php artisan key:generate
7. Run php artisan migrate
8. Run php artisan serve
9. Go to http://localhost:8000/  

- To Generate optimized (autoload) files run the following command!
= composer dump-autoload  

# if you are importing Large DB in your Local Mysql 
- follow the following steps! 
  For windows, first of all open xampp and right click Config and open php.ini file.
  After in php.ini file update this code 

  post_max_size = 800M
  upload_max_filesize = 800M
  max_execution_time = 6000
  max_input_time = 6000
  memory_limit = 1000M 


