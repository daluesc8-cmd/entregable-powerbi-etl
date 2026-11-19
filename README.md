# RetailPro — Proyecto de análisis de ventas

## Descripción del proyecto

RetailPro es un proyecto de análisis de datos orientado a estudiar el comportamiento de las ventas de una distribuidora de tecnología. El objetivo es organizar la información comercial mediante SQL y obtener datos que permitan analizar las ventas, los productos, los clientes y las categorías.

## Objetivos

- Construir una base de datos relacional.
- Consultar y analizar información comercial mediante SQL.
- Identificar productos con mayor facturación.
- Analizar la evolución mensual de las ventas.
- Relacionar información de ventas, clientes, productos y categorías.
- Preparar información para su posterior análisis y visualización.

## Herramientas utilizadas

- **Microsoft SQL Server:** creación y administración de la base de datos.
- **SQL:** consultas, filtros, agrupaciones y relaciones entre tablas.
- **GitHub:** almacenamiento y documentación de los archivos del proyecto.

## Estructura del proyecto

Los principales archivos SQL son:

- `ventas_tech_db.sql`: creación de la base de datos, tablas e inserción de datos de ejemplo.
- `m4_consultas_negocio.sql`: consultas de análisis comercial, resumen mensual y ranking de productos.
- `m5_consultas_joins.sql`: consultas con INNER JOIN y LEFT JOIN para relacionar tablas.

## Modelo de datos

La base de datos `Ventas_Tech_DB` contiene las siguientes tablas:

- **ventas:** registra las operaciones comerciales.
- **clientes:** contiene información de los clientes.
- **productos:** almacena los productos comercializados.
- **categorias:** clasifica los productos.

## Cómo ejecutar los scripts

1. Abrir Microsoft SQL Server Management Studio.
2. Ejecutar primero `ventas_tech_db.sql` para crear la base de datos y sus tablas.
3. Ejecutar `m4_consultas_negocio.sql` para obtener indicadores y resultados comerciales.
4. Ejecutar `m5_consultas_joins.sql` para realizar consultas que relacionan las distintas tablas.
5. Revisar los resultados en la ventana de consultas de SQL Server Management Studio.

**Importante:** el archivo de creación contiene instrucciones `DROP TABLE IF EXISTS`. Estas instrucciones eliminan las tablas existentes antes de volver a crearlas. Ejecutar el archivo con precaución si se desean conservar datos cargados previamente.

## Análisis realizado

Entre los análisis desarrollados se encuentran:

- Resumen ejecutivo mensual de facturación.
- Ranking de productos según facturación.
- Identificación de clientes recurrentes.
- Comparación de productos según su facturación.
- Integración de datos mediante consultas JOIN.

## Autoría

Proyecto académico RetailPro — Análisis de datos con SQL.
