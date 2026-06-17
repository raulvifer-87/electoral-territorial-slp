# Electoral Territorial Analytics — San Luis Potosí

Proyecto de análisis territorial electoral orientado a construir indicadores, métricas y visualizaciones municipales para San Luis Potosí.

El objetivo es transformar datos electorales en información útil para análisis público, consultoría, investigación social, toma de decisiones territoriales y construcción de tableros de seguimiento.

## Objetivo del proyecto

Construir una base analítica municipal para observar patrones electorales en San Luis Potosí a partir de indicadores como participación, margen de victoria, competitividad, fragmentación electoral y distribución territorial del voto.

## Alcance inicial

La versión inicial del proyecto trabaja a nivel municipal. Esta escala permite integrar resultados electorales con cartografía e indicadores socioeconómicos sin entrar todavía a la complejidad de secciones electorales.

En etapas posteriores, el proyecto podrá ampliarse a análisis por sección electoral, distrito local o distrito federal, dependiendo de la disponibilidad y calidad de los datos.

## Preguntas de análisis

1. ¿Qué municipios presentan mayor y menor participación electoral?
2. ¿Dónde se observan elecciones más competitivas?
3. ¿Qué municipios muestran mayor margen de victoria?
4. ¿Cómo se distribuye territorialmente el voto por partido o coalición?
5. ¿Qué regiones muestran patrones electorales diferenciados?
6. ¿Cómo pueden integrarse indicadores socioeconómicos para interpretar los resultados territoriales?

## Indicadores iniciales

| Indicador               | Fórmula / criterio                | Interpretación                                 |
| ----------------------- | --------------------------------- | ---------------------------------------------- |
| Participación electoral | votos totales / lista nominal     | Mide el nivel de movilización electoral        |
| Margen de victoria      | % primer lugar - % segundo lugar  | Identifica territorios dominantes o competidos |
| Competitividad          | 1 - margen de victoria            | Mide qué tan cerrada fue la elección           |
| Ganador municipal       | partido o coalición con más votos | Identifica fuerza territorial dominante        |
| Fragmentación electoral | número efectivo de partidos       | Mide dispersión o concentración del voto       |

## Fuentes de datos previstas

* INE / Cómputos 2024 para resultados federales.
* CEEPAC San Luis Potosí para resultados locales.
* INEGI Marco Geoestadístico para cartografía municipal.
* INEGI / CONEVAL para variables socioeconómicas de contexto.

## Stack técnico

* Python
* pandas
* numpy
* matplotlib
* geopandas
* folium
* plotly
* Jupyter Notebook
* GitHub

## Estructura del repositorio

```text
electoral-territorial-slp/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ notebooks/
│  └─ 01_data_sources_and_scope.ipynb
├─ reports/
│  └─ project_scope.md
└─ data/
   ├─ raw/
   └─ processed/
```

## Carpetas principales

* `notebooks/`: notebooks de exploración, limpieza, cálculo de indicadores y mapas.
* `reports/`: documentación del proyecto, interpretación de indicadores y hallazgos.
* `data/raw/`: datos originales descargados de fuentes oficiales.
* `data/processed/`: bases limpias listas para análisis.

## Roadmap

### v0.1 — Definición del proyecto

* Crear repositorio.
* Definir alcance municipal.
* Documentar fuentes de datos.
* Definir indicadores iniciales.

### v0.2 — Base electoral municipal

* Descargar resultados electorales.
* Limpiar nombres de municipios.
* Construir tabla municipal de votos.
* Calcular participación y porcentajes de voto.

### v0.3 — Indicadores territoriales

* Calcular margen de victoria.
* Calcular competitividad.
* Identificar ganador municipal.
* Calcular fragmentación electoral.

### v0.4 — Mapas

* Descargar cartografía municipal.
* Unir datos electorales con geometrías.
* Crear mapas de participación, margen y competitividad.

### v0.5 — Interpretación

* Redactar hallazgos principales.
* Identificar regiones con patrones diferenciados.
* Preparar reporte ejecutivo para portafolio.

## Valor del proyecto

Este proyecto muestra habilidades aplicadas de análisis de datos públicos, construcción de indicadores, lectura territorial y visualización geográfica. Es útil para roles de Data Analyst, Business Analyst, consultoría pública, análisis electoral, investigación social y visualización de datos.

## Estado del proyecto

En desarrollo.
