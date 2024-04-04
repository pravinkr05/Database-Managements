# Database-Managements

## Introduction 🔰

* __Data__ - collection of text, symobls, observations, facts type of content. eg - item's weight (having numerical value), Person Name(descriptive value)
* __Information__ - data with some meaning. eg- In a village 100 people are rich. here data is providing some specific information.
* __Need__ - data is new oil for business growth today. eg - amazon takes feedback from customers after deliering the product and observed customer demands. It helps them to make informed decision (decision based on true facts of the market). 

* __Database__ - A system or place where data is stored in such a way that data can be easily accessed, managed(other kind of operations on data) and updated.
* __DBMS (Database Management systems)__ - A software that connects database to the user (via API) and provides set of commands through which the data can be stored and manipulated. ex- modern DBMS single software MySQL, and Oracle provides both fascility storing and manipulating(CRUD operation) the data.
  MySQL = Database + DBMS

* __File System disadv / dbms adv__ -
   1. Data changing at one place may not changed at other place if data is repeated.
   2. Data repetition exist when required to stored same data in other file.
   3. Accesing specific data directly from huge data is difficult.
   4. Security on data is difficult when some data is only can see manager not programmer.
   5. Integrity problems - can not  apply some condition while accesing data via file such as balance > 100.

  In file system - we need to write all programs whenever do the CRUD operations.
  In DBMS software - all necessary programs are grouped together and built a software where only using some commands can run those programs and perform that operations (CRUD). 
  IBM database is 1st database.
      many other advantage are also available.


  ## Keywords meaning
  * Abstraction - as a end user we don't have information how dbms operations internally working. just we used data storing and manipulating operation.
  * Instance - At a time/particular moment, stored information in database called db instance.
    
    <img src="https://github.com/pravinkr05/Database-Managements/assets/128983635/63511daf-5e36-4871-9604-399892a5e21d" width="248">
    
  * db schema - logical and visual representation of entire database. how the database is constructed. it contains attributes and constraints(id!=NULL).

    <img src="https://github.com/pravinkr05/Database-Managements/assets/128983635/a1bb3dd0-743a-4e30-865a-768cfb2700fd" width="248">

    Create Student{
    string name; int id;
    }

    * Database language -
         * DDL - data definition language. used to define database schema with some constraints. eg - create student(id NOT NULL)... a student schema
         * DML - data manipulation language. used to manipulate the data via CRUD operation. eg. select * from student;
         * Query language used in retrieval of information.
         * eg - SQL is working as both DML and DDL. JDBC is api that provides java program to access database(SQL server).

      * DBMS Architechture - entire system working model
         * T1 -  client, server and db all present in local host.
         * T2 - entire system only can access single organization only. client and database. client can direct use database and can do wrong things.
         * T3 - entire system in three parts. client(Frontend), server(Backend) and database(Mongodb). client can't send any wrong query. app server filter the incoming query.

         

      

    
    

    



