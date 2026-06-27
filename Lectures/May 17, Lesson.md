# MySQL

```mysql
create database mydb;

show databases;

use mydb;

show tables;

create table Persons (
	PersonID int PRIMARY KEY,
	LastName varchar(255) NOT NULL,
	FirstName varchar(255),
	Address varchar(255),
	City varchar(255),
);

insert into Persons values (123, 'Davtyan', 'Sergey', 'Teryan 20', 'Yerevan');

select * from Persons;

select count(*) from Persons; # number of rows

update table Persons set City='Arinj' where name='Sergey';

select * from Persons;

insert into Persons values (123, 'Davtyan', 'Sergey', 'Teryan 20', 'Yerevan'); # error: duplicate key, because ID is primary key

desc Persons; # description

insert into Persons values (125, 'Davtyan', 'Sergey', 'Teryan 20', 'Yerevan'); # ok

delete from Persons where PersonID=123;

```

`uptime` command (bash) - how is load_average calculated?

# Install Wordpress on Linux

https://ubuntu.com/tutorials/install-and-configure-wordpress

Also, host wordpress on a subdomain. You can ask for subdomain from SergeyD.
Watch the recording and follow the steps.

EC2 LAMP (?)



