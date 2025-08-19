Propósito del Análisis

El propósito de este análisis es obtener una visión clara del desempeño de cuatro tiendas en línea, usando una base de datos que contiene información sobre productos vendidos, categorías, precios, calificaciones de clientes, métodos de pago, ubicación geográfica, y costos de envío.

Ejemplos de Gráficos e Insights Obtenidos
1. Ingreso total por tienda
Se utilizó sum() sobre la columna "Precio".

Insight: La tienda 3 generó mayores ingresos que las otras.

Categorías más vendidas
Agrupadas con groupby() y contadas con .count().
Insight: "Electrodomésticos" y "Muebles" son categorías líderes en varias tiendas.

Calificación promedio
Calculadas con .mean() sobre la columna "Calificación".
Insight: La Tienda 4 tiene la calificación promedio más alta (mayor satisfacción del cliente).

Productos más y menos vendidos
Contados con value_counts().
Insight: Algunos productos destacan en todas las tiendas mientras otros tienen ventas mínimas o únicas.

Costo de envío promedio
Se usó .mean() sobre "Costo de envío".
Insight: La Tienda 2 tiene los costos de envío promedio más altos.

Instrucciones para Ejecutar el Notebook
Abre el notebook en Google Colab o súbelo desde tu cuenta de Google Drive.
Ejecuta las celdas una por una con Shift + Enter, empezando por la que importa las librerías.
Si quieres visualizar los gráficos, asegúrate de ejecutar las celdas de visualización donde matplotlib debe estar importado.
