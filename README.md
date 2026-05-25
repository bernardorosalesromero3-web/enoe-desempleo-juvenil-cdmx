# ENOE CDMX 2020-2025 — Desempleo Juvenil

Análisis del mercado laboral juvenil en la Ciudad de México (2020-2025) 
usando microdatos del ENOE (INEGI). Pipeline de ingesta en Databricks 
con Unity Catalog y EDA enfocado en desempleo, informalidad y 
condiciones de ocupación.

## Estructura

- `01_Pipelines_ENOE.ipynb` — Ingesta y construcción de tabla maestra
- `02_EDA_desempleo_juvenil.ipynb` — Análisis exploratorio
- `03_Modelo_Catboost.ipynb` — Modelo predictivo de desempleo (AUC 0.65)

## Dataset

Fuente: ENOE (Encuesta Nacional de Ocupación y Empleo) — INEGI  
Período: 2020 T1 — 2025 T2  
Población objetivo: Jóvenes de 18 a 29 años en la Ciudad de México

## Hallazgos principales

- Pico de desempleo juvenil de 15.4% en 2021-T1 por COVID-19
- Recuperación desigual por sexo, brecha persistente de 2 puntos porcentuales
- Informalidad estructural por encima del 50% sin mejora en 5 años
- Brecha salarial de 12.5% entre hombres y mujeres jóvenes ocupados

## Tecnologías

Python, PySpark, Databricks, Unity Catalog, CatBoost, pandas, seaborn

## Autor

Bernardo Rosales — [LinkedIn](https://linkedin.com/in/bernardo-rosales-romero)
## Dataset

Fuente: [ENOE — INEGI](https://www.inegi.org.mx/programas/enoe/15ymas/)  
Período: 2020 T1 — 2025 T2  
Población objetivo: Jóvenes de 18 a 29 años en la Ciudad de México
