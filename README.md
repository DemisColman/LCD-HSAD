# Herramientas de Software para el Análisis de Datos
## Sprint 3
### Objetivo
Aplicar conocimientos de bases de datos relacionales (SQLAlchemy), versionado de datos (DVC) y búsqueda por similitud visual (ChromaDB) para profesionalizar el sistema portuario.

### Introducción y contexto
El sistema ha crecido en volumen y complejidad. El equipo de desarrollo portuario necesita:

1. **Persistencia estructurada**: pasar de CSVs a una base de datos relacional con ORM.
2. **Auditoría de cambios**: poder rastrear qué versión del dataset se usó en cada análisis.
3. **Identificación visual de buques**: dado que la OCR no siempre funciona bien, el sistema debe poder identificar un buque por similitud visual de su imagen, sin depender del texto.
