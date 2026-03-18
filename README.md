# Proyecto-SQL
Entrega del proyecto final de SQL
Descripción del Proyecto
El proyecto a consistido en el análisis de la base de datos Sakila, utilizando SQL en DBeaver para extraer la información sobre:
Comportamiento de clientes
Películas, actores, clasificaciones e interés de cliente.
Rendimiento de productos (películas)
Patrones de alquiler
Visualización de ingresos
El objetivo adicional a las consultas ha sido transformar datos en insights accionables de negocio, para la toma de decisiones.

Estructura de la Base de Datos Sakila
El análisis se ha realizado sobre un la base de datos relacional y compuesto por tablas como:
film → información de películas
actor → datos de actores
film_actor → relación muchos a muchos
category / film_category → clasificación de películas
customer → clientes
rental → alquileres
payment → pagos
inventory → stock disponible
Estas tablas nos permiten analizar el negocio desde múltiples visiones y resultados requeridos: producto, cliente y transacciones.

Proceso de Trabajo
1.	Exploración de datos
Identificación de las tablas para la solución de las preguntas
Comprensión de las relaciones a utilizar 
Validación de los campos relevantes
2.	Se realizaron búsquedas y consultas básicas para:
Filtrar datos desde condicionales, Seleccionar información específica de columnas identificadas, Ordenar resultados y usar agregaciones.

3. Uso y aprendizaje de Agregaciones y métricas como:
COUNT() → número de registros
SUM() → ingresos totales
AVG() → promedios
MAX() / MIN() → valores extremos

4. Uso y aprendizaje de los Análisis por grupos para las identificaciones tendencias y patrones como:
GROUP BY, HAVING. Para identificación de categorías mas frecuentadas, clientes con mayor actividad, actores recurrentes etc.


5. Adecuado uso e identificación de los distintos tipos de JOINs como:
INNER JOIN → relaciones directas
LEFT JOIN → incluir datos faltantes
CROSS JOIN → combinaciones completas

6. aplicar Subconsultas para la realización de comparaciones, promedios, filtros etc

7. Creación de tablas temporales 

Principales Insights del Análisis
Se calculó el total de ingresos generados por la empresa.
Permite establecer una base para análisis de rentabilidad.
Identificación de los clientes con mayor gasto.
Existencia de clientes de alto valor (heavy users).

Nos ha permitido observar una alta concentración de ingresos en un grupo reducido de clientes lo que nos da para realizar estrategias de fidelización o recompensa para los clientes recurrentes. Identificación de películas más alquiladas.

Al hacer análisis sobre las películas, títulos y preferencias de actoras nos permite organizar y optimizar catálogos para hacer promociones sobre las películas con mayor interés en los usuarios y clasificar las comunicaciones basadas en categorías, edades, intereses, etc.  Al tener datos y análisis de patrones de alquiler, como frecuencia etc. podemos activar a través de los patrones de consumo, incentivos como recompensas para los usuarios

Identificación de comportamiento del Negocio
Los análisis nos permiten detectar y ver:
Segmentos de clientes según comportamiento
Identificar productos de alto rendimiento
Optimizar estrategias comerciales
Detectar oportunidades de crecimiento
El enfoque Estratégico que se puede percibir es:
Más allá de SQL, este proyecto demuestra la capacidad de traducir datos en decisiones de negocio y aplicar lógica analítica a entornos reales para conectar análisis de datos con estrategias de negocio (marketing, clientes, producto)


