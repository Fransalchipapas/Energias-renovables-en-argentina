# Análisis y Predicción de la Matriz de Generación de Energías Renovables en Argentina (2011–2020)

> Nota: Todos los registros provienen del sector dedicado a Energías Alternativas, las mediciones se realizaron 
Mensualmente y los datos conforman el total nacional, pero están detallados a nivel Provincial.

## Objetivos específicos

1. Reunir y documentar datasets públicos relacionados.
2. Filtrar o integrar la información necesaria.
3. Realizar un análisis exploratorio de datos (AED/EDA) utilizando Pandas y visualizaciones.
4. Limpiar y transformar las variables necesarias.
5. Preparar los datos para regresión y clasificación.
6. Comparar modelos supervisados mediante métricas apropiadas y controlar el overfitting mediante partición de datos y ajuste de hiperparámetros.
7. Desarrollar un modelo de clustering, explicando el criterio utilizado.
8. Documentar las decisiones, resultados y limitaciones del proyecto.

> Nota: los objetivos concretos de regresión y clasificación se definirán después de inspeccionar las columnas y la calidad de los datasets reales. No se crearán objetivos artificiales solo para cumplir una técnica.

## Fuentes iniciales previstas

CAMMESA

Las URLs exactas, versiones y fechas de descarga se registrarán en `docs/fuentes.md`.

## Tecnologías

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Estructura

```text
Energias_renovables_en_Argentina/
├── data/
│   ├── raw/
│   └── processed/
├── docs/
├── kaggle/
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

## Creamos el repositorio en GitHub
```text
Empezamos creando el repositorio:                      git init
Guardamos la primera version en ese repositorio local: git add .
                                                       git commit -m "Inicializar proyecto"
Vamos a GitHub y creamos el repositorio nuevo:         (https://github.com/Fransalchipapas/analisis-proyectos-mineros-mendoza-.git)
Conectamos el repositorio desde la terminal:           git remote add origin https://github.com/Fransalchipapas/analisis-proyectos-mineros-mendoza-.git
Verificamos                                             git remote -v  (get, push)
Renombramos la rama actual del main                    git branch -M main 
Subimos los comits locales a GitHub                    git push -u origin main

git pull origin main                                   actualizamos los datos desde github a local

```