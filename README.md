# DesafioAlura_Store_DataSC
Este proyecto fue desarrollado como parte del desafío de ciencia de datos propuesto en el curso de **Alura LATAM**. Por Carlos Sebastian Gómez Carrilo
# Desafío Alura Store - Análisis de Datos

Este proyecto fue desarrollado como parte del desafío de ciencia de datos propuesto en el curso de **Alura LATAM**.

El objetivo del análisis es evaluar el rendimiento de ventas, desempeño logístico y satisfacción de clientes en **cuatro tiendas** pertenecientes a la cadena **Alura Store**, para **identificar oportunidades de mejora** y **apoyar la toma de decisiones estratégicas**.

---
## Tecnologías Utilizadas

- **Python 3.11**
- **Pandas** para manipulación y análisis de datos tabulares.
- **Matplotlib** para visualización de gráficos básicos.
- **Seaborn** para gráficos avanzados y estilizados.

---
## Procesamiento de Datos

- Se realizaron las siguientes acciones de preparación:

- Conversión de la columna Fecha de Compra al tipo datetime.

- Creación de una nueva columna Tienda para identificar el origen de cada venta.

- Unión de los cuatro datasets en un único DataFrame para análisis consolidado.

- Revisión de nulos (NaN) y validación de tipos de datos (dtypes).

- Estandarización de nombres de variables y estructuras.

##Análisis Realizados
- Se desarrollaron los siguientes análisis:

- Ingresos Totales por Tienda
➔ Suma de precios vendidos agrupados por tienda.

- Cantidad de Productos Vendidos por Tienda
➔ Conteo de productos por tienda.

- Ingreso Promedio por Venta
➔ Promedio del precio de venta en cada tienda.

- Lugares de Compra más Frecuentes
➔ Ciudades o municipios con mayor cantidad de compras.

- Métodos de Pago más Utilizados
➔ Formas de pago preferidas por los clientes.

- Ranking de Productos Más Vendidos
➔ Top de productos individuales más comercializados.

- Ranking de Categorías Más Vendidas
➔ Análisis por categoría general de productos.

Cada análisis fue complementado con visualizaciones gráficas claras y etiquetas explicativas.

## 🗂Estructura del Proyecto

```plaintext
DesafioAlura_DS_CSGC/
│
├── dataset/
│    ├── tienda_1.csv
│    ├── tienda_2.csv
│    ├── tienda_3.csv
│    └── tienda_4.csv
│
├── notebooks/
│    └── desafio_alura_store.ipynb
│
├── images/
│    └── (Gráficos exportados opcionales)
│
└── README.md
