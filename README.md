# alura-store-data-sciencie
Proyecto del curso de Data Science: análisis de tiendas Alura Store.

# Análisis de Tiendas Minoristas y Recomendación de Venta

## Introducción

Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas minoristas (`Tienda 1`, `Tienda 2`, `Tienda 3`, `Tienda 4`) para proporcionar una recomendación fundamentada sobre cuál de ellas sería la mejor opción para vender. Se examinarán diversas métricas financieras, operativas y de satisfacción del cliente para ofrecer una perspectiva integral.

## Descripción del Dataset

El dataset utilizado contiene información detallada sobre las transacciones de las cuatro tiendas. Cada tienda tiene un archivo CSV separado con las siguientes columnas:

*   `Producto`: Nombre del producto vendido.
*   `Categoría del Producto`: Categoría a la que pertenece el producto.
*   `Precio`: Precio de venta del producto.
*   `Costo de envío`: Costo asociado al envío del producto.
*   `Fecha de Compra`: Fecha en que se realizó la compra.
*   `Vendedor`: Nombre del vendedor.
*   `Lugar de Compra`: Ciudad donde se realizó la compra.
*   `Calificación`: Calificación del cliente sobre la compra (1-5).
*   `Método de pago`: Método de pago utilizado.
*   `Cantidad de cuotas`: Número de cuotas si el pago fue a crédito.
*   `lat`: Latitud del lugar de compra.
*   `lon`: Longitud del lugar de compra.

## Análisis Realizados

Se llevaron a cabo los siguientes análisis clave para cada tienda:

1.  **Análisis de Facturación**: Cálculo del ingreso total de cada tienda.
2.  **Ventas por Categoría**: Identificación de las categorías de productos más vendidas.
3.  **Calificación Promedio de la Tienda**: Evaluación de la satisfacción del cliente a través de la calificación promedio.
4.  **Productos Más y Menos Vendidos**: Determinación de los productos con mayor y menor demanda.
5.  **Costo de Envío Promedio**: Cálculo del costo promedio de envío para cada tienda.
6.  **Análisis Geográfico**: Visualización de la distribución geográfica de las ventas (heatmap y mapa interactivo).

## Hallazgos Clave

*   La **Tienda 1** es la de mayor facturación.
*   Las categorías de **Electrónicos** y **Muebles** son consistentemente las más vendidas en la mayoría de las tiendas.
*   Las calificaciones promedio son muy similares entre todas las tiendas, indicando una satisfacción del cliente consistente.
*   Los productos más vendidos varían según la especialización de cada tienda.
*   Los costos de envío promedio son también muy similares entre las tiendas.

## Recomendación Final

Basado en el análisis exhaustivo de ingresos, ventas por categoría, satisfacción del cliente y costos operativos, se recomienda al Sr. Juan vender la **Tienda 1**. Esta tienda ofrece la combinación más robusta de altos ingresos y fuerte demanda en categorías lucrativas, manteniendo un nivel competitivo en satisfacción del cliente y eficiencia operativa.

## Visualizaciones

Este proyecto incluye diversas visualizaciones para facilitar la comprensión de los datos, tales como:

*   Gráfico de barras de ingresos totales por tienda.
*   Gráfico de barras de ventas por categoría por tienda.
*   Gráfico de pastel de la proporción del costo de envío promedio total por tienda.
*   Gráfico de barras del costo de envío promedio por tienda.
*   Heatmap de concentración de ventas geográficas.
*   Mapa interactivo de las transacciones (usando Folium).

## Tecnologías Usadas

*   Python (lenguaje de programación)
*   Pandas (manipulación y análisis de datos)
*   Matplotlib (visualización de datos estáticos)
*   Seaborn (visualización de datos estadísticos)
*   Folium (visualización de datos geográficos interactivos)

## Cómo Ejecutar el Proyecto

1.  **Clonar el repositorio** (si aplica).
2.  **Instalar las dependencias**: `pip install pandas matplotlib seaborn folium`
3.  **Ejecutar el notebook**: Abrir `nombre_del_notebook.ipynb` (o el archivo principal del proyecto) en un entorno compatible (Jupyter Notebook, Google Colab, etc.) y ejecutar las celdas en orden. Asegúrese de tener acceso a los archivos CSV de las tiendas o de que las URLs de descarga de los datos sean válidas.
```
