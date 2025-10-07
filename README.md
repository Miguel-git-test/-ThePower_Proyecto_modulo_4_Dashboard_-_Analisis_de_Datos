# -ThePower_Proyecto_modulo_4_Dashboard_-_Analisis_de_Datos
Repositorio para presentar el dashboard del proyecto del módulo 4 del máster de Data Analytics de The Power
📊 Dashboard Coffee Shop
Descripción del Proyecto

Este proyecto consiste en el desarrollo de un Dashboard interactivo de ventas para una Coffee Shop, diseñado en Excel.
El objetivo principal es explorar, analizar y visualizar las ventas con el fin de identificar tendencias, patrones y métricas clave que ayuden a comprender mejor el rendimiento del negocio.
Para ello, se siguieron estos pasos:

•	Exploración inicial de los datos a través de tablas dinámicas (pestaña “T_Dinam”) para detectar relaciones y tendencias.

•	Revisión y comprensión de las columnas disponibles (pestaña “Nota”).

•	Enriquecimiento de los datos mediante la creación de nuevas variables derivadas, como:

o	Día de la semana y del mes a partir de las fechas.

o	Hora del día de la transacción.

o	Cálculo del Total_Amount a partir del precio unitario y las cantidades.

•	Diseño del dashboard siguiendo el patrón visual en Z, colocando la información más general y relevante en la parte superior izquierda y el detalle en la parte inferior derecha.

•	Uso de una paleta de colores suaves con predominio de tonos verdes para mantener una estética clara y agradable.

•	Implementación de filtros interactivos (por fecha, tienda y categorías de producto) para mejorar la exploración de los datos.

Los datos fueron obtenidos desde Kaggle: Coffee Shop Sales Dataset (https://www.kaggle.com/code/ahmedabbas757/coffee-shop-sales/input), y el proyecto se trabajó directamente sobre el archivo original en formato 
Excel (.xlsx).

Estructura del Proyecto

El archivo principal del proyecto es:

•	Dashboard Coffee Shop Final.xlsx

Dentro del Excel se incluyen varias pestañas con funciones específicas:

•	Datos → Dataset crudo descargado desde Kaggle.

•	Notas → Documentación sobre el significado de cada columna del dataset.

•	Dash → Visualización principal con métricas, gráficos y filtros.

•	T_Dinam → Tablas dinámicas utilizadas para la exploración inicial.

Instalación y Requisitos

Para visualizar y utilizar el dashboard es necesario contar con:

•	Microsoft Excel (versión 2013 o superior).

No se requieren librerías ni herramientas adicionales, ya que el proyecto se desarrolló íntegramente en Excel.

Resultados y Conclusiones

Del análisis realizado a través del dashboard se destacan los siguientes hallazgos:

•	Existe poca variación en las ventas entre los diferentes días de la semana.

•	Las tres tiendas tienen ingresos similares, aunque presentan diferencias en el comportamiento horario de sus clientes.

•	La mayor afluencia de clientes ocurre entre 8:00 y 10:00 de la mañana, manteniéndose un flujo constante desde las 11:00 hasta el cierre a las 20:00.

•	Café y té representan aproximadamente dos tercios de la facturación.

•	Dentro de estas categorías, “Barista Expresso” y “Brewed Chai Tea” destacan como los productos principales en las tres tiendas.

•	4 productos (de un total de 32) concentran el 45% de los ingresos, mientras que 15 productos generan solo el 9% (según columna “CA” de la hoja “T_Dinam”).

•	El 90% de los ingresos provienen de productos con precio menor a 5 €, que representan a su vez el 98% de las transacciones (columnas “FO” y “FV”).

Estos resultados permiten identificar los productos más estratégicos, los horarios clave de consumo y la relevancia de los artículos de bajo precio en el volumen de ventas.

Próximos Pasos 

•	Integrar más variables externas (ejemplo: clima, campañas de marketing).

•	Migrar el dashboard a otra herramienta (Power BI, Tableau) para una mayor interactividad.

Autores
- Miguel Sanz
- www.linkedin.com/in/miguelsanzgarzon

