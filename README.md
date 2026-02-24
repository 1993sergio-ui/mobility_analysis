# Análisis de Movilidad Urbana y Productividad Económica en LATAM 🌎🚗

Este proyecto tiene como objetivo evaluar la relación entre la **movilidad urbana** (congestión vehicular) y la **productividad económica** (PIB per cápita) en las principales ciudades de Latinoamérica. El análisis busca identificar prioridades estratégicas para la inversión en infraestructura de transporte basándose en datos reales.

## 📋 Descripción del Proyecto

Utilizando datos de **TomTom Traffic Index 2024** y **OECD City Economy**, el análisis integra métricas de tráfico, desempleo, población y PIB para responder a la pregunta: *¿En qué ciudades la congestión está frenando el potencial económico?*

### Características principales:
- **Limpieza de datos:** Procesamiento de formatos numéricos, estandarización de nombres (snake_case) y manejo de fechas.
- **Análisis Exploratorio (EDA):** Identificación de valores atípicos y promedios anuales de tráfico por ciudad.
- **Merge de Datasets:** Combinación de indicadores económicos y de movilidad.
- **Visualización:** Uso de Boxplots e Histogramas para entender la distribución del tráfico y la riqueza en la región.

## 🛠️ Herramientas Utilizadas

- **Python 3.x**
- **Pandas:** Manipulación y limpieza de datos.
- **NumPy:** Operaciones matemáticas.
- **Seaborn & Matplotlib:** Visualizaciones estadísticas y gráficos de relación.
- **Jupyter Notebook:** Entorno de desarrollo del análisis.

## 🚀 Estructura del Análisis

1. **Carga y Exploración:** Conexión con los datasets originales.
2. **Limpieza y Preparación:** Estandarización de tipos de datos y corrección de formatos numéricos.
3. **Extracción y Filtrado:** Enfoque en el año más reciente (2024).
4. **Resumen de Movilidad:** Cálculo de promedios anuales de `jams_delay` y tiempos de viaje.
5. **Unión de Datos:** Creación de un dataset unificado (Movilidad + Economía).
6. **Análisis Visual:** Identificación de patrones y outliers.

## 📊 Hallazgos Clave

* **Ciudad Prioritaria:** Tras el análisis, **Bogotá** fue identificada como una prioridad absoluta debido a sus niveles de congestión extrema en contraste con su PIB.
* **Impacto Económico:** Se observa que el tiempo perdido en el tráfico representa una pérdida de competitividad sistémica para ciudades con PIB moderado.
* **Recomendación:** Priorizar financiamiento en sistemas de transporte masivo y soluciones de *Smart Traffic* en el clúster Bogotá-Lima.

## 📁 Archivos en el repositorio

- `ladb_mobility_economy_project.ipynb`: Notebook principal con todo el código y análisis.
- `/data`:  Carpeta que debería contener los archivos CSV utilizados.
- `/charts`:  Carpeta que debería contener los graficos generados.

---
Análisis desarrollado para el Laboratorio de Análisis de Datos (LADB).
