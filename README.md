# Fundación Potenciar Solidario - Análisis de Ingresos y Egresos
El presente proyecto es un trabajo final realizado en el curso "Análisis de Datos" ofrecido por Guayerd, en conjunto con IBM y la Fundación Potenciar Solidario.
La base de datos fue otorgada por la Fundación Potenciar Solidario con el fin de realizar este trabajo, por lo que los datos y registros NO son reales y la
información podría no ser precisa.

## Objetivo del Proyecto
El objetivo del proyecto es realizar un anáisis detallado de los ingresos por donaciones y los egresos por gastos de la Fundación Potenciar Solidario en el 
período de 2018 a 2024. A través de la transformación y limpieza de los datos, se garantiza que los datos sean consistentes y adecuados para el análisis y para 
el armado de un informe interactivo que permita extraer insights valiosos.

## Herramientas Utilizadas
* Power BI Desktop para la creación del dashboard interactivo.
* Python (Jupyter Notebook) para la limpieza, transformación y análisis preliminar de los datos.
* Pandas, NumPy, Matplotlib y Seaborn: Librerías clave para el manejo de los datos y la generación de grágicos en Python.
* Archivos CSV como fuente de datos principal para el análisis.

## Visualizaciones Incluídas:
* Gráficos de barras y líneas para analizar tendencias temporales.
* Mapas geográficos interactivos para representar distribución por regiones.
* Indicadores clave (KPIs) para un resumen rápido de métricas importantes.

## Estructura del Proyecto
```
F:.
│   FundacionPotenciarSolidario_Informe_de_Ingresos_y_Egresos.pbix
│   fundacion_potenciar_solidario.ipynb
│   
├───data
│   ├───clean
│   │       activos_limpio.csv
│   │       donantes_limpio.csv
│   │       inactivos_limpio.csv
│   │       proveedores_limpio.csv
│   │       
│   └───original
│           detalles.csv
│           donantes.csv
│           proveedores.csv
│           
├───resources
│   └───images
│           fondo1.jpg
│           fondo2.jpg
│           guayerd.png
│           ibm.png
│           img_caratula.png
│           potenciar_solidario.png
│           
└───visuals
        fundacion_potenciar_solidario_INFORME.pdf
        page_1.jpg
        page_2.jpg
        page_3.jpg
        page_4.jpg
        page_5.jpg
        page_6.jpg
```

En donde en la carpeta "original" se encuentran los datos originales, tal cual fueron entregados por la Fundación, en la carpeta "clean" se encuentran los datos limpios y transformados, en "images" están las imágenes utilizadas para el dashboard en Power BI, y en "visuals" hay elementos visuales para una visualización rápida del informe, como un archivo .pdf e imágenes de las diferentes páginas del mismo.
