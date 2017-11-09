# Simple Wordpress Powered By Composer and Docker

## Setting Up Locally
### In www folder:
* `composer install`
### In root directory
* `docker-compose up -d`
* Database Setup
** Connect to Database:
*** `docker exect -it {hash} bash`
*** `mysql -u root -p`
*** Password is root
** `use wp;`
** `source /var/support/yourbackedup.sql`