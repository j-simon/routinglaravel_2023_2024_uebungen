
**Übung 16**: Migriere deine Migrations

Führe die Migration in deiner Vagrant Box aus. 



**Lösung:**

```

php artisan migrate

```



**Test:**

im MySql Server gibt es nun einige Tabellen in der routinglaravel Datenbank: 

```
überprüfen per phpMyAdmin oder auf der cmd:

mysql -uroot -proot

USE routinglaravel;

SHOW TABLES;

DESCRIBE posts;

DESCRIBE interests;

```

Vorsicht: eventuell gab es einen Fehler in der .env Datei!
