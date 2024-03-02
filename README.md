HOW To Install MYSQL, and configure it.

Install MYSQL Installer installed, needed admin rights.
Configured at default TCP/IP port of 3306
root users password iamhappywithmylife

Configure server as a service, and following is service name.
MySQL80

FOLLOWING CODE IS WRITTEN IN SQL WORKBENCH TO CREATE SCHEMA AND EMPTY TABLE inside that schema

create database if not exists newdb default character set utf8 collate utf8_general_ci;
USE newdb;

Create Table if not exists accounts
(
id int(11) NOT NULL auto_increment,
username varchar(50) NOT NULL,
password varchar(255) NOT NULL,
PRIMARY KEY (id)

)DEFAULT CHARSET =utf8;
