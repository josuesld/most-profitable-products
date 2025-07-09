# Proyecto de Análisis de Ventas de Productos

Este repositorio contiene un proyecto de análisis de datos simple enfocado en ventas de productos, utilizando Python con las librerías `pandas` y `plotly`. El objetivo es demostrar cómo realizar análisis básicos de datos, calcular KPIs y visualizar información clave.

## Contenido del Repositorio

-   `datos_productos.xlsx`: Este archivo Excel contiene los datos de ventas utilizados para el análisis. Incluye información sobre `Producto`, `Cantidad` vendida, `Precio` y `Fecha` de la venta.
-   `analisis_ventas.ipynb`: Este es el Jupyter Notebook principal donde se realizó todo el análisis. Contiene el código Python para:
    -   Cargar los datos desde el archivo `datos_productos.xlsx`.
    -   Identificar el producto más vendido por cantidad.
    -   Ordenar los productos por precio (del más alto al más bajo).
    -   Generar un gráfico de columnas interactivo (usando Plotly) para visualizar la cantidad total vendida por cada producto.
    -   Calcular Indicadores Clave de Desempeño (KPIs) como el total de unidades vendidas, el ingreso total y el ingreso promedio por venta.

## Análisis Realizados

1.  **Producto Más Vendido:** Se identificó el producto con la mayor cantidad de unidades vendidas.
2.  **Precios de Productos:** Se listaron los productos ordenados por su precio, del más caro al más barato.
3.  **Visualización de Ventas:** Un gráfico de barras interactivo muestra la distribución de las ventas por producto, permitiendo una comprensión rápida de cuáles son los artículos más y menos populares.
4.  **KPIs de Ventas:** Se calcularon métricas importantes para evaluar el rendimiento de las ventas.

## Cómo Ejecutar el Proyecto

Para replicar el análisis y ver los gráficos interactivos, sigue estos pasos:

1.  **Clona este repositorio:**
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    cd tu_repositorio
    ```
    *(Recuerda reemplazar `tu_usuario` y `tu_repositorio` con los datos de tu cuenta y repositorio de GitHub.)*

2.  **Asegúrate de tener Python y Jupyter instalados.** Si no, puedes instalarlos a través de Anaconda o pip.

3.  **Instala las librerías necesarias:**
    ```bash
    pip install pandas openpyxl plotly
    ```

4.  **Abre el Jupyter Notebook:**
    ```bash
    jupyter notebook analisis_ventas.ipynb
    ```

5.  Una vez abierto el notebook en tu navegador, puedes ejecutar las celdas secuencialmente para ver los resultados y los gráficos.

