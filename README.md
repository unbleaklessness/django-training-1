# MySQL:

## Setup MySQL:
- Installation: `sudo apt-get install mysql-server`.
- Start MySQL: `sudo service start mysql`.
- Login to MySQL: `sudo mysql -u root -p`.
- Create a new user: `create user 'admin'@'localhost' identified by '1234'`.
- Grant privileges to a new user: `grant all privileges on *.* to 'admin'@'localhost' with grant option`.
- Flush privileges: `flush privileges`.
- Now you can login to MySQL with newely created account.

## Install MySQL for Python:
- Install library: `sudo apt-get install libmysqlclient-dev`.
- Install Python library: `pip install mysqlclient`.

## Adminer:
- Install PHP and extensions: `sudo apt-get install php php-mysql`.
- Download Adminer.
- Put Adminer PHP script in to separate directory.
- Run `php -S localhost:8080` in this direcotry.

# Manage.py:
- `runserver` - Start the Django server.
- `startapp <app_name>` - Create a new app.
- `migrate` - Update databse with migrations.
- `makemigrations` - Create new migrations.