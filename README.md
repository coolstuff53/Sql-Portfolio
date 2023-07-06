# Sql-Portfolio
Show case my SQL skills
/** clothes
Shirts (11) (13) (9)
Pants (8) (20) (10)
Hats (13) (10) (7)
Shoes (20) (30) (8)
**/

CREATE TABLE clothes (id INTEGER PRIMARY KEY, clothing TEXT, quantity INTEGER, price INTEGER, rating integer );

INSERT INTO clothes VALUES (1, "Shirts", 11, 13, 9);
INSERT INTO clothes VALUES (2, "Pants", 8, 20, 10);
INSERT INTO clothes VALUES (3, "Hats", 13, 10, 7);
INSERT INTO clothes VALUES (4, "Shoes", 20, 30, 8);

Select sum(quantity) from clothes;
Select sum(price) from clothes


sum(quantity)
52
sum(price)
73
