## Forma Normales en Bases de Datos (Normalizacion)
### 1NF (Primera Forma Normal):
- Elimina grupos repetitivos.
- Cada celda de la tabla debe contener un solo valor.
- Cada registro debe ser único.

### 2NF (Segunda Forma Normal):
- Cumple con 1NF.
- Todos los atributos no clave deben depender completamente de la clave primaria.
- Elimina dependencias parciales.

### 3NF (Tercera Forma Normal):
- Cumple con 2NF.
- No debe haber dependencias transitivas entre atributos no clave.
- Cada atributo no clave debe depender únicamente de la clave primaria.

### Boyce-Codd Normal Form (BCNF):
- Una versión más estricta de 3NF.
- Cada determinante debe ser una clave candidata. ejemplo: Si A -> B, entonces A debe ser una clave candidata.

### 4NF (Cuarta Forma Normal):
- Cumple con BCNF.
- No debe haber dependencias multivaluadas.

### 5NF (Quinta Forma Normal):
- Cumple con 4NF.
- Descompone las tablas para eliminar redundancias derivadas de dependencias de unión.
- Asegura que las tablas no puedan ser descompuestas sin pérdida de información.
- una tabla solo debe existir si no puede ser creada mediante el join de otras tablas.

### 6NF (Sexta Forma Normal):
- Cumple con 5NF.
- Descompone las tablas para eliminar dependencias temporales.  

### 7NF (Séptima Forma Normal):
- Forma normal avanzada que aborda dependencias más complejas y específicas.
- Rara vez se utiliza en la práctica.