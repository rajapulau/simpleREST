# simpleREST
hello simple REST webservice PHP

NOTE : PLEASE INPUT QUERY SQL OWN.. I DON'T PUT SQL QUERY ON API

This is sample to create table
```
CREATE TABLE IF NOT EXISTS `customers` (
  `customerNumber` int(11) NOT NULL AUTO_INCREMENT,
  `customerName` varchar(50) NOT NULL,
  `email` varchar(50) NOT NULL,
  `address` varchar(50) NOT NULL,
  `city` varchar(50) NOT NULL,
  `state` varchar(50) DEFAULT NULL,
  `postalCode` varchar(15) DEFAULT NULL,
  `country` varchar(50) NOT NULL,
  PRIMARY KEY (`customerNumber`)
);
```
