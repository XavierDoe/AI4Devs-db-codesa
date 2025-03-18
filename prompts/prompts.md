## Objetivo
Actualizar la base de datos para operar el flujo completo de aplicación para diversas posiciones, expandiendo la estructura de datos actual y aplicando buenas prácticas de diseño de bases de datos.

---

## Instrucciones  

### 1. Conversión del ERD a SQL  
- Utiliza el diagrama ERD proporcionado en formato Mermaid para generar un script SQL que defina la estructura de la base de datos.  
- Asegúrate de incluir:  
  - Creación de tablas  
  - Definición de relaciones  
  - Claves primarias (PK)  
  - Claves foráneas (FK)  
- Aplica buenas prácticas como:  
  - Normalización de la base de datos  
  - Definición de índices para optimizar el rendimiento  

### 2. Análisis y Expansión de la Base de Datos  
- Analiza el código actual y el script SQL proporcionado.  
- Expande la estructura de datos utilizando migraciones de Prisma.  
- Asegúrate de que las nuevas entidades y relaciones estén correctamente implementadas.  

### 3. Verificación y Pruebas  
- Utiliza herramientas visuales como **PGAdmin** para conectarte a la base de datos PostgreSQL y verificar la estructura creada.  
- Prueba la base de datos:  
  - Inserta datos de ejemplo.  
  - Realiza consultas para validar su funcionamiento.  
- Asegúrate de que las relaciones entre tablas (ejemplo: `COMPANY → EMPLOYEE`, `POSITION → APPLICATION`) funcionen correctamente.  

---

## Entregables Esperados  
✅ Un **script SQL completo** que refleje la estructura del ERD proporcionado, incluyendo índices y normalización.  
✅ Un **archivo de migración de Prisma** que expanda la base de datos actual.  
✅ **Capturas de pantalla o evidencia** de la verificación en PGAdmin, mostrando:  
  - La estructura de la base de datos.  
  - Consultas de prueba.  

---

## Notas Adicionales  
📌 Asegúrate de que todas las tablas y relaciones estén correctamente implementadas en el script SQL.  
📌 Documenta cualquier decisión tomada durante la normalización o la creación de índices.  
📌 Si encuentras inconsistencias en el ERD, propón mejoras y justifícalas.  

---

## Mejoras Aplicadas  
✔ **Claridad:** Se especifican los pasos a seguir de manera detallada y estructurada.  
✔ **Contexto:** Se incluye el diagrama ERD para referencia y se explica cómo debe ser utilizado.  
✔ **Entregables:** Se definen claramente los resultados esperados (`script SQL`, `migración de Prisma`, `evidencia de pruebas`).  
✔ **Enfoque Práctico:** Se enfatiza la importancia de verificar y probar la base de datos con herramientas como PGAdmin.  
✔ **Buenas Prácticas:** Se reitera la necesidad de aplicar normalización, índices y documentación.  
