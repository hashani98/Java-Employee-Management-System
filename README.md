Employee Management System is a distributed application, developed to maintain the details of employees working in any organization. It maintains the information about the personal details of their employees, also the details about the payroll system which enable to generate the payslip. The application is actually a suite of applications developed using Java.

Language Used -  Core Java 
Concept Used - Swing
IDE Used - Eclipse
Database Used - MySQL

Execute these queries one bye one in your MySQL.

1 - create database with name project3

create database project3;

2 - use database you have just created

use project3;

3 - Start creating tables inside the database, project3, create login table first

create table login(username varchar(20), password varchar(20));

4 - create employee table to store the information of employees

create table employee(name varchar(25), fname varchar(30), age varchar(10), dob varchar(20), address varchar(50), phone varchar(20), email varchar(30), education varchar(15), post varchar(15), aadhar varchar(20), emp_id varchar(10));
