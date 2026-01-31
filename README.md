
mysql> use hotel;
Database changed
mysql> show tables;
+-----------------+
| Tables_in_hotel |
+-----------------+
| reservations    |
+-----------------+
1 row in set (0.01 sec)

mysql> select*from reservations;
+----------------+------------+------------+---------------------+
| reservation_id | guest_name | contact_no | checkout            |
+----------------+------------+------------+---------------------+
|              1 | rishi      | 9856983421 | 2025-05-10 10:09:04 |
|              2 | vassu      | 9856983562 | 2025-07-11 09:44:08 |
|              3 | rishika    | 9856972305 | 2025-07-04 02:36:56 |
+----------------+------------+------------+---------------------+
3 rows in set (0.00 sec)
