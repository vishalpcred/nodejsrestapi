# nodejsrestapi
Building REST APIs with MySQL and Node.js

REST is an acronym for Representational State Transfer. It is web standards architecture and HTTP Protocol. 

Tools: Node.js, MySql, Text editor (Atom, Sublime, Visual Studio etc), Postman 

/* Start with create database from phpmyadmin */

CREATE DATABASE mydb;

CREATE TABLE `tasks` (
  `id` int(11) NOT NULL,
  `task` varchar(200) NOT NULL,
  `status` tinyint(1) NOT NULL DEFAULT '1',
  `created_at` datetime NOT NULL DEFAULT CURRENT_TIMESTAMP
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

ALTER TABLE `tasks`
  ADD PRIMARY KEY (`id`);

ALTER TABLE `tasks`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=1;

/* Clone the project to local machine */

git clone <url> command in terminal 



