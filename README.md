# JOIN-AND-INNER-JOIN

## Merhabalar



Aşağıdaki sorgu senaryolarını **dvdrental** örnek veri tabanı üzerinden gerçekleştiriniz.

1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.


2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.


3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.



## Cevaplar :


1. 
```sql


SELECT country , city FROM country 
INNER JOIN city ON country.country_id = city.country_id;


```


2. 
```sql


SELECT first_name , last_name FROM customer 
INNER JOIN payment ON customer.customer_id = payment.customer_id;


```


3. 
```sql


SELECT first_name, last_name FROM customer 
INNER JOIN rental ON customer.customer_id = rental.customer_id;


```

**KOLAY GELSINIZ**
