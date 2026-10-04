## Objetivo del proyecto: 

Entender el uso de llamadas, mensajes de ConnectaTel para detectar patrones y segmentos, se **exploro**, **limpio** y **analizo** estos datos para construir un **perfil estadístico** de los clientes, para detectar **comportamientos atípicos** y crear **segmentos de clientes**.

## Datasets utilizados:

las rutas dentro del entorno:
- **plans.csv** **`/datasets/plans.csv`** → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)  
- **users.csv** **`/datasets/users\_latam.csv`** → información de los clientes (edad, ciudad, fecha de registro, plan, churn)  
- **usage.csv** **`/datasets/usage.csv`** → detalle del **uso real** de los servicios (llamadas y mensajes)

## Etapas del análisis: 

limpieza de datos
cálculo de outliers
segmentación
visualizaciones
insights ejecutivos.

## Cómo ejecutar el notebook: 

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**
3. Verifica que estén instaladas estas librerías: pandas, numpy, seaborn, matplotlib. 

## Guía de reproducción: 

1. Abre `notebooks/S7 Versión-Estudiante-Proyecto-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. el notebook carga los archivos directamente desde la carpeta /datasets/ del entorno.
