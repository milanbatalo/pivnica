# pivnica (brewery)
Overview

pivnica (brewery) application is a very simple web app created using AngularJS, Java 7, Spring, JPA, Hibernate, Maven. Application provides RESTful services to create, update, delete/edit and buy items. Search is optional.  Frontend part is slightly touched with bootstrap.

Database Connection
You need to create a database named "pivnica" in your local MySQL database to work with this application. Note: There is a pivnica.sql file in sql directory, which execute and insert a user 'root' with password 'root'. spring.datasource.username and spring.datasource.password is also set to root & root in application.properties. spring.jpa.hibernate.ddl-auto is set to "create" for testing.

Goals

Planning to modify frontend part of application, provide log in mechanism for users and make shopping cart to buy a beer.
