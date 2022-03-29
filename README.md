# oprs_payroll_system
Open payroll management system 

## Purpose of the project

The project is aiming to grant a platform for the management of payrolls.
It is a web application that allows the management of payrolls but also gives a set of features that faciliate daily 
tasks.

### Architecture 

![Architecture](./resources/diagrams/app_architecture.jpg)


### Site map

![Sitemap](./resources/diagrams/persona-based-task-flow-diagram%20(1).png)


## Requirements
 
 You need to have the following requirements installed to run the project:
 * composer
 * php
 * mysql
 * phpmyadmin

### Database

The database which is used in this project is called `payroll` and it is managed with mysql(community edition).

## Installation
 
 You can install the project by running the following command:
  * git clone ![](https://github.com/Pericles001/oprs_payroll_system.git)
  * cd oprs_payroll_system
  * composer install
  * mv .env.example .env
  * php artisan key:generate
  * php artisan migrate

## Usage

 Once you have installed the application, you should run it with:
  * php artisan serve

 You can connect yourself by using the already given credentials.

### Credentials 

  * username: | `root` | `root` | 
  * password: | `root` | `root` |

## Contributors
![AUTHORS](./AUTHORS)
