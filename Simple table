-- create a table
CREATE TABLE INSTRUCTOR (
ins_id INTEGER PRIMARY KEY,
lastname VARCHAR(60) NOT NULL,
firstname VARCHAR(60) NOT NULL,
city VARCHAR(30), 
country CHAR(2)
);

INSERT INTO INSTRUCTOR 
(ins_id, lastname, firstname, city, country) 
VALUES
(1,'Ahuja','Rav','Toronto', 'CA'),
(2,'Chong','Raul','Toronto', 'CA'),
(3,'Vasudevan','Hima','Chicago','US');

UPDATE INSTRUCTOR
SET city = 'Markham'
WHERE ins_id = 1;

DELETE FROM INSTRUCTOR
WHERE ins_id = 2;

SELECT * FROM INSTRUCTOR
