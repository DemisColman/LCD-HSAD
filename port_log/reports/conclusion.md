
# Conclusión - Sprint 1
## Evaluación de la calidad del dataset heredado: porcentaje de registros descartados y tipos de error más frecuentes.
El porcentaje de registros descartados es de 29.8%.
El principal error fueron los datos nulos o caracteres inválidos. Mayoritareamente en las columnas: mátricula, tonelaje declarado y velocidad de ingreso.

## Patrones de infracción detectados: ¿en qué turnos, muelles y tipos de carga se concentran?
Analizando los resultados obtenidos, podemos concluir que no hay concentración de infracciones ni por turno, ni por muelle ni por tipo de carga.

## Reflexión sobre el impacto de incorporar estos datos sin limpieza previa al nuevo sistema.
Incorporar directamente los datos heredados al nuevo sistema podría generar resultados incorrectos en los análisis y reportes. Fechas y horas inválidas, matrículas o muelles sin normalizar, valores faltantes y observaciones extremas
podrían producir duraciones incorrectas, duplicar categorías y distorsionar indicadores estadísticos.

## Al menos una propuesta concreta de mejora para el proceso de captura de datos en el puerto.
Agregar validaciones para los campos que sean críticos en los análisis que se realizan a futuro:
- Que no se permitan ingresos vacíos o nulos.
- Que sean coherentes: que la fecha de egreso no sea anterior a la de ingreso.
- Que los datos pre-existentes esten normalizados dentro de un catálogo.
- Validación de rangos para ciertos campos: fechas dentro de un periodo razonable.
