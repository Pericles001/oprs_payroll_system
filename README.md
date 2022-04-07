# oprs_payroll_system
Open payroll management system 

## Purpose of the project

The project is aiming to grant a platform for the management of payrolls.
It is a web application that allows the management of payrolls but also gives a set of features that faciliate daily 
tasks.

### Technologies

![BLADE TEMPLATE](https://img.shields.io/badge/blade-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![JQUERY](https://img.shields.io/badge/jquery-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)  ![Github](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)



### Architecture 

![Architecture](./resources/diagrams/app_architecture.jpg)


### Site map

![Sitemap](./resources/diagrams/site_map.drawio.png)


### Users

Two users are defined: 
 * Administrator 
 * Employee


### Admin features

  The project has the following features:

  
  * **User management**: It allows the management of users via (creation/update/deletion).
  * **Payroll management**: It allows the management of payrolls(creation/update/deletion).
  * **Budget generation**: It allows the generation of budgets .
  * **Budget management**: It allows the management of budgets (deletion) .
  * **Leaves management**: It allows the management of employees leaves .
  * **Faq management**: It allows the management of frequently asked questions (creation/update/deletion).

### Employee features

  * **Payroll visualisation**: It allows the employee to view his payrolls at each generation.
  * **Payroll simulation**: It allows employee to generate a payroll based on his/her current salary and a future date.
  * **Events management**: It allows employee to manage his/her events with a calendar .
  * **Task management**: It is a feature that allows employee to manage his tasks todo in a day more accuretely.
  * **Chat**: It allows employee to chat with other employees.
  * **Leaves visualisation**: It allows employee to ask or view his/her leaves.


#### Login page

![login page](./resources/screenshots/0_login_screen.png)



#### Welcome page

![profile page](./resources/screenshots/1_welcome_page.png)

#### Profile update page
![update profile](./resources/screenshots/2_profile_modification.png)

#### Employee creation page
![employee creation](./resources/screenshots/3_create_employee.png) 

#### Users list page
![users list](./resources/screenshots/4_list_user.png)


#### Payroll management page
![payroll management](./resources/screenshots/5_manage_payroll.png)



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
  * cd oprs_payroll_system/app
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

*Credentials will be given sooner*

## Contributors
![AUTHORS](./AUTHORS)
