# MariaDB / MySQL

**Licencia:** GPL (comunitario)

## Descripción
SGBD relacional popular y compatible con ecosistemas LAMP; MySQL cuenta con edición comunitaria abierta.

## Sistemas operativos compatibles
- Windows
- macOS
- Linux

## Enlace oficial
- https://mariadb.org/

### Ejemplo básico (cliente mysql)
```bash
mysql -u root -p
CREATE DATABASE demo;
USE demo;
CREATE TABLE tareas(id INT PRIMARY KEY AUTO_INCREMENT, titulo VARCHAR(100));
INSERT INTO tareas(titulo) VALUES ('Hola MariaDB/MySQL');
SELECT * FROM tareas;
```

