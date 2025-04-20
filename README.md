# Análisis de Tiendas y Decisión sobre la Tienda a Eliminar

Este proyecto realiza un análisis comparativo entre cuatro tiendas con el objetivo de determinar cuál debería ser eliminada basándose en varias métricas clave, como los **ingresos totales**, **categorías de productos más y menos vendidos**, **calificaciones promedio de los clientes**, **productos más y menos vendidos**, y **costos de envío promedio**. 

El análisis se realiza utilizando **Python**, **pandas** y **matplotlib**, y la visualización de los datos se lleva a cabo con gráficos generados a partir de estos datos.

## Propósito

El propósito de este análisis es ayudar al **Sr. Juan** a tomar una decisión informada sobre cuál tienda debe eliminarse de su red de ventas, con base en los datos recolectados sobre ventas, productos, costos y calificaciones de los clientes.

## Análisis Realizado

Se evaluaron las siguientes métricas para cada tienda:

1. **Ingreso Total por Tienda**: Para ver cuál tienda genera más ingresos.
2. **Cantidad de Productos Vendidos por Categoría**: Para comparar la cantidad de productos vendidos por cada categoría en cada tienda.
3. **Calificación Promedio de los Clientes**: Para medir la satisfacción general de los clientes de cada tienda.
4. **Productos Más y Menos Vendidos**: Para identificar los productos con mayor y menor demanda.
5. **Costo de Envío Promedio por Tienda**: Para evaluar los costos operativos asociados con cada tienda.

## Gráficos Generados

El análisis incluye los siguientes gráficos para comparar el desempeño de cada tienda:

1. **Gráfico de torta** para mostrar el **ingreso total por tienda**.
2. **Gráfico de barras agrupadas** para mostrar la **cantidad de productos vendidos por categoría**.
3. **Gráfico de barras** para comparar las **calificaciones promedio de los clientes**.
4. **Gráfico de dispersión** para analizar la relación entre el **precio** y el **costo de envío**.

## Justificación de la Elección de la Tienda a Eliminar

Tras analizar los ingresos, ventas, calificaciones y costos de envío, se recomienda eliminar **Tienda 4** debido a los siguientes motivos:

- **Ingreso Total Bajo**: Tienda 4 tiene el ingreso total más bajo entre todas las tiendas.
- **Bajas Ventas en Categorías Clave**: Tienda 4 tiene un bajo rendimiento en ventas de productos de alta demanda como **Electrónica** y **Muebles**.
- **Calificaciones Promedio Similares**: Aunque las calificaciones son similares en todas las tiendas, el bajo rendimiento de Tienda 4 en ventas hace que sea una opción para eliminar.
- **Costo de Envío Bajo, pero Baja Rentabilidad**: A pesar de tener un bajo costo de envío, Tienda 4 no compensa con su bajo rendimiento en ventas.

## Requisitos

Para ejecutar el proyecto en tu máquina local, asegúrate de tener instalado Python y las siguientes librerías:

- `pandas`
- `matplotlib`

Puedes instalar las librerías necesarias con:

```bash
pip install pandas matplotlib seaborn

#en este caso no es necesario ya que se realizo junto con google colaboraty
