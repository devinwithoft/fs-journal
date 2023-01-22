# MVC







 repository layer


 manually writing data base


CREATE TABLE syrups(
  id INT NOT NULL *AUTO_INCREMENT* PRIMARY KEY *(MEANS THAT THIS IS THE WAY THE TABLE WILL BE SORTED)*,
  name *VARCHAR(20) NOT NULL [REQUIRED] COMMENT 'description of the product'
  or *TEXT which is VARCHAR(HUGE)
  viscosity INT NOT NULL DEFAULT 5, 
  color VARCHAR(15),
  flavor VARCHAR(20) NOT NULL DEFAULT 'Maple',
  canadian BOOLEAN NOT NULL DEFAULT true
); put chracter set here

potentially set character set *(example directly above table)*
default charset utf8 COMMENT '';

bools become tinyint
0 false
1 true


DROP TABLE syrups; *deletes table*


INSERT into syrups;
(name, viscosity, color, flavor, canadian) *order matters* 
VALUES
("Grandma Scyamore's", 7, 'brown, 'Maple', false);


SELECT * FROM syrups; all

SELECT name, id, viscosity from SYRUPS; getting columns *Can select multiple tables*

can customize column names on result

name AS syrup_name, *(using format from above)*


customize search

SELECT 
*
FROM syrups
WHERE viscosity >= 8 AND canadian = 1; *can use boolean as true here* 

sort custom search

SELECT
*
FROM syrups 
WHERE viscosity < 8
ORDER BY viscosity;



uhh make sure to put connection string appsettingsDevelopmentJson being sure to insert name of database

jdbc:mysql://SG-Devinwithoft-7116-mysql-master.servers.mongodirector.com:3306/Whatever?user name=sgroot&password=RJfdQ5x%40jsVgypqS

IDbConnection interface


INSRT INTO cars
(make, model year, price, imgUrl, description, color)
VALUES
(@make, @model, @year, @price, @imgUrl, @description, @color)


server ready funtion launch json





VIRTUAL 

GO INTO THING YOU WANT POPULATED ON ACCOUNT MODEL

NEW MODEL * : FIRSTTHING
{
  this things id 
}







