# Análisis y Predicción de la Matriz de Generación de Energías Renovables en Argentina (2011–2020)
> Nota: Todos los registros provienen del sector dedicado a Energías Alternativas, las mediciones se realizaron 
Mensualmente y los datos conforman el total nacional, pero están detallados a nivel Provincial.
## Fuente del proyecto:
El dataset fue levantado de CAMMESA (Compañía Administradora del Mercado Mayorista Eléctrico S.A.), quienes coordinan la 
operación del Sistema Argentino de Interconexión (SADI) y administran el mercado eléctrico mayorista de Argentina
## Resumen del proyecto
Analizamos los datos oficiales de CAMMESA para estudiar la participación de las energías renovables en Argentina.
Realizamos limpieza, análisis exploratorio y visualización de datos para identificar tendencias y evaluar el aporte de 
estas fuentes a la generación eléctrica nacional
## Objetivo del proyecto
Predecir la cantidad de energía renovable mensual que generan las provincias según el tipo de fuente y el mes del año
para anticipar la oferta eléctrica y crear un plan estratégico.
## Análisis exploratorio
Descubrimos muchas columnas con información redundante propia del sector que fueron removidas, así como también la
columna de energía nuclear fue eliminada por generar una amplia dispersión en la generación real. Se crearon columnas 
con información temporal como, mes y año 

## Objetivos específicos

1. Reunir y documentar datasets públicos relacionados.
2. Filtrar o integrar la información necesaria.
3. Realizar un análisis exploratorio de datos (AED/EDA) utilizando Pandas y visualizaciones.
4. Limpiar y transformar las variables necesarias.
5. Preparar los datos para regresión y clasificación.
6. Comparar modelos supervisados mediante métricas apropiadas y controlar el overfitting mediante partición de datos y ajuste de hiperparámetros.
7. Desarrollar un modelo de clustering, explicando el criterio utilizado.
8. Documentar las decisiones, resultados y limitaciones del proyecto.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estructura del repositorio

```text
Energias_renovables_en_Argentina/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── .gitignore
├── README.md
└── requirements.txt
```
## Orden de trabajo

1. Selección y documentación de datasets.
2. AED / EDA.
3. Limpieza y transformación.
4. Preparación de variables.
5. Regresión.
6. Clasificación.
7. Clustering.
8. Evaluación y conclusiones.



