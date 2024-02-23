## Description

```bash
PHP CodeIgniter 3 Users Crud
```

![image](https://github.com/jhhg04/PHP-CI-CrudUsers-Codernauta/assets/52834318/a2b5b7b4-1fcb-4af3-b686-11a566838b00)

![image](https://github.com/jhhg04/PHP-CI-CrudUsers-Codernauta/assets/52834318/c85047ae-4f2b-4d17-b348-bc91b2738aa8)


## Installation

```bash
PHP version 5.6 or newer is recommended.
Download complete project
If use Xampp, copy the project in htdocs folder
```

## Create DB

```bash
CREATE DATABASE crudci;		  
USE crudci;		  
CREATE TABLE personas(id int not null primary key auto_increment, nombre varchar(30) not null, ap varchar(30) not null, am varchar(30) not null, fn date not null, genero char not null);
SHOW tables;
DESC personas;
```

## Running the app

```bash
open http://localhost/CRUD-CI
```
