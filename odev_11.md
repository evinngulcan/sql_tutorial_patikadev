Ödev-11 Soru Çözümleri

1-actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

---- (
select first_name from actor
);
union
(select first_name from customer
);

2-actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

---- (
select first_name from actor
);
intersect
(select first_name from customer
);

3-actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.

---- (
select first_name from actor
);
except
(select first_name from customer
);

4-İlk 3 sorguyu tekrar eden veriler için de yapalım.

---- (
SELECT first_name
FROM actor
)
UNION ALL
(
SELECT first_name
FROM
customer
);


(
SELECT first_name
FROM actor
)
INTERSECT
(
SELECT first_name
FROM
customer
);



(
SELECT first_name
FROM actor
)
EXCEPT ALL
(
SELECT first_name
FROM
customer
);
