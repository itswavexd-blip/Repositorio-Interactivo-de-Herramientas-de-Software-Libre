# PostgreSQL

**Licencia:** PostgreSQL License (similar a BSD)

## Descripción
SGBD objeto-relacional potente y extensible, compatible con SQL y cargas de trabajo exigentes.

## Sistemas operativos compatibles
- Windows
- macOS
- Linux
- BSD
- Otros

## Enlace oficial
- https://www.postgresql.org/

### Ejemplo básico
```bash
# Entrar a la consola
psql -U postgres
# Crear base y tabla
CREATE DATABASE demo;
\c demo
CREATE TABLE notas(id SERIAL PRIMARY KEY, titulo TEXT);
INSERT INTO notas(titulo) VALUES ('Hola PostgreSQL');
SELECT * FROM notas;
```

