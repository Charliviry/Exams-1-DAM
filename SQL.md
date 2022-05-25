010420221036
Status: #basesdedatos #UF2
Tags:[[SQL]]
# SQL
## El elemento Table
#### Creación de una Tabla
```sql
CREATE TABLE nombre tabla(campo1, campo2, campo3,...);
```

#### Indicar propiedades de campos
```sql
CREATE TABLE nombreTabla (campo1 tipo (longitud), campo2 tipo (longitud), campo3 tipo (longitud),...);
```
#### Ejemplo
```sql
CREATE TABLE departamento (deptNum INT (4), deptNombre VARCHAR (50), deptLocalidad VARCHAR (50));
```

```sql
SELECT *
FROM clientes 
LEFT JOIN pedidos
ON clientes.Codigo_de_cliente = pedidos.Codigo_de_cliente
WHERE pedidos.Codigo_de_cliente IS NULL
```
---
# References
Videos profe