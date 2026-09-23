# Changelog

## [Ejercicio 7]

- Evaluación de la calidad del dataset heredado.
- Análisis de los principales patrones de infracción.
- Evaluación del impacto de incorporar datos sin limpieza previa.
- Propuesta de mejora para el proceso de captura de datos.
- Generación del archivo `port_log/reports/conclusion.md`.

## [Ejercicio 6]

- Cálculo del porcentaje de infracciones con fechas inválidas.
- Cálculo del porcentaje de infracciones con horas inválidas.
- Identificación del tipo de carga más frecuente en infracciones.
- Identificación del origen más frecuente entre los buques infractores.
- Cálculo de la duración promedio de estadía en muelle.

## [Ejercicio 5]

- Creación de gráfico: Top 10 matrículas reincidentes.
- Creación de gráfico: Infracciones por turno del día.
- Creación de gráfico: Infracciones por mes.
- Creación de gráfico: Distribución del exceso de velocidad.
- Creación de gráfico: Exceso promedio por muelle.
- Creación de gráfico: Fechas válidas vs inválidas.

## [Ejercicio 4]

- Creación de la clase `PortAnalyzer`.
- Implementación del ranking de matrículas infractoras.
- Agrupación de infracciones por turno del día.
- Cálculo del exceso promedio de velocidad.
- Agrupación de infracciones por muelle.
- Agrupación de infracciones por tipo de carga.

## [Ejercicio 3]

- Normalización de fechas de ingreso y egreso.
- Normalización de horas de ingreso y egreso.
- Cálculo de la duración de permanencia en horas.
- Normalización de matrículas y muelles.
- Eliminación de registros con nulos en columnas críticas.
- Comparación de los métodos IQR y Z-score y eliminación de outliers mediante IQR.
- Cálculo del exceso de velocidad real y con 5% de tolerancia.
- Eliminación de registros sin infracción.
- Exportación del dataset limpio en `port_log/data/interim/port_movements.csv`.
- Exportación del resumen estadístico en `port_log/reports/summary_sprint1.csv`.

## [Ejercicio 2]

- Descarga del dataset de movimientos portuarios en `port_log/data/raw`.
- Visualización de las primeras y últimas cinco filas del dataset.
- Análisis de los tipos de datos y detección de columnas que requieren conversión.
- Identificación y conteo de valores nulos por columna.
- Cálculo del porcentaje de valores correctos por columna.

## [Ejercicio 1]

- Creación y configuración de la rama `Sprint_1`.
- Creación de la estructura de directorios del proyecto `port_log`.
- Creación del archivo `README.md` con el objetivo, la introducción y el contexto del Sprint 1.