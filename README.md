Scheduled Manager DAO api

this api use data access object DAO to set the mysql database

tomcat SERVER need to be configured in order to run in IDE Eclipse

java server page is used in this api, model request - response not REST

mysql setting:

CREATE SCHEMA scheduled;

CREATE TABLE scheduled.users ( id INT NOT NULL AUTO_INCREMENT,
 name VARCHAR(45) NOT NULL, 
email VARCHAR(45) NOT NULL
, country VARCHAR(45) NOT NULL, PRIMARY KEY (id));