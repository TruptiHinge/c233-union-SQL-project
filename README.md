# c233-union-SQL-project

(select country from customers)
UNION
(select country from suppliers);

(select country from customers)
UNION ALL
(select country from suppliers);

(select country from customers)
Intersect
(select country from suppliers);
