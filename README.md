Домашнее задание Волкова Дмитрия SQL_Index

Задание 1


Напишите запрос к учебной базе данных, который вернёт процентное отношение общего размера всех индексов к общему размеру всех таблиц.

![SQL3_1_1](https://github.com/dvolkov15/SQL_Index/blob/main/SQL3_1_1.png)


Задание 2


Выполните explain analyze следующего запроса:

![SQL3_2_1](https://github.com/dvolkov15/SQL_Index/blob/main/SQL3_2_1.png)


перечислите узкие места;

1) В запросе берутся 5 не объедененых таблиц
2) В улсовии нет смысла использовать 
p.payment_date = r.rental_date and r.customer_id = c.customer_id and i.inventory_id = r.inventory_id
необходимо сократить



оптимизируйте запрос: внесите корректировки по использованию операторов, при необходимости добавьте индексы.

![SQL3_2_2](https://github.com/dvolkov15/SQL_Index/blob/main/SQL3_2_2.png)
