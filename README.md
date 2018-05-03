Comandos Posgress
=================
```
su - postgres

psql

```

Listar bases de datos:

```
\list
```

Usar una base de datos:

```
\c sales
```

Listar tables

```
\dt
```

Create table

```
CREATE TABLE leads (id INTEGER PRIMARY KEY, name VARCHAR);
```

salir psql

```
\q
```

:poop: :poop: :poop:

psql postgres://cecum:password@172.18.0.3:5432/sample -c "SELECT count(id) FROM employees;"