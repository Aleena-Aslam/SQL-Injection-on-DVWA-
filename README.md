# SQL-Injection-on-DVWA-

Learn SQL injection using Damn Vulnerable  Web App

**DVWA**

The kali Linux DVWA package contains a PHP/MySQL web application that is damn vulnerable. Its main goal is to be an aid for security professionals to test their skills and tools in a legal environment, help web developers better understand the processes of securing web applications and to aid both students & teachers to learn about web application security in a controlled class room environment.

The aim of DVWA is to practice some of the most common web vulnerabilities, with various levels of difficulty, with a simple straightforward interface. There are both documented and undocumented vulnerabilities with this software. 

WARNING: Do not upload it to your hosting provider’s public html folder or any Internet facing servers, as they will be compromised.

**Dependencies:**

- adduser
- apache2
- libapache2-mod-php
- mariadb-server
- nginx
- php8.4
- php8.4-fpm
- php8.4-gd
- php8.4-mysql

**SQL**

Structured Qurey Language. Allow to access a database. use ANSI and ISO standard computer language. The most standard is SQL9075:2016. SQL can:

- Execute the database
- Retrive data from a database
- Insert new records in database
- Delete records from a database
- Update records in a database

SQL injection takes advantage of web application flaws that might let a user maliciously manipulate a web application’s back-end database.SQL Injection is a common security vulnerability that arises from letting attacker supplied data become SQL code. This happens when programmers assemble SQL queries either by string interpolation or by concatenating SQL commands with user supplied data.

In order to exploit the SQL injection vulnerabilities need to figure out how the query is built in order to inject  parameter in the situation that the query will remain true. The next step is to identify what kind of database is runing on the back-end in order to construct the queries accordingly.

**PHP-intrusion Detection system**
Also know as Web Application Firewall (WAF). PHP-IDS works by filtering any user supplied input against a blacklist of potentially malicious code.
