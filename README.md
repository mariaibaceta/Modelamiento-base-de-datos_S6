# Proyecto Semana 6 – Modelamiento de Bases de Datos

## 📌 Descripción
Implementación de un **modelo relacional** en Oracle para el **Consultorio Médico Municipalidad Santa Gema**, en base al caso entregado en la actividad formativa de la semana 6.  
El script incluye la creación de tablas, definición de restricciones y modificaciones posteriores según las reglas de negocio.

## 📂 Contenido del repositorio
- `PRY2204_S6_MariaIbaceta.sql` → Script con:
  - Eliminación previa de objetos (`DROP TABLE ... CASCADE CONSTRAINTS`)
  - Creación de tablas (Caso 1)
  - Restricciones de PK, FK, UNIQUE y CHECK
  - Secuencias `IDENTITY` solicitadas
  - Alteraciones de tablas (Caso 2)

## ⚙️ Requisitos
- Oracle SQL Developer o cliente SQL compatible.
- Usuario creado previamente (`PRY2204_S6`) según instrucciones del curso.

## ▶️ Instrucciones de ejecución
1. Abrir Oracle SQL Developer.
2. Conectarse con el usuario **PRY2204_S6**.
3. Ejecutar el script `PRY2204_S6_MariaIbaceta.sql` **en orden secuencial completo**.
4. Verificar que las tablas y restricciones se hayan creado correctamente con:
   ```sql
   SELECT table_name FROM user_tables;
   ```

## 📑 Notas importantes
- El script está **comentado por bloques** para facilitar su lectura.
- Incluye todas las reglas de negocio y restricciones pedidas en la pauta de evaluación.
- Listo para ser subido tanto a **AVA** como a **GitHub**.

---

✍️ Elaborado por: **María Ibaceta**  
📅 Curso: PRY2204 – Semana 6
