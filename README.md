# data-analysis-practice
Proyecto de análisis de datos en desarrollo usando Excel y Power Query
# Análisis de Turismo en Áreas Protegidas – Región de Los Lagos (2024)

## Descripción
Proyecto de análisis de datos enfocado en el turismo en Chile, utilizando información oficial del Sistema Nacional de Áreas Silvestres Protegidas del Estado (SNASPE).
El análisis se centra en la Región de Los Lagos durante el año 2024 y busca generar indicadores clave y un dashboard ejecutivo reutilizable.

## Objetivo
Analizar el comportamiento de las visitas a áreas protegidas para:
- Identificar patrones mensuales de afluencia.
- Analizar la composición de visitantes por nacionalidad y demografía.
- Construir KPIs claros para apoyar la toma de decisiones.

## Dataset
- **Fuente:** Reporte de Visitas SNASPE (datos oficiales)
- **Región:** Los Lagos
- **Año:** 2024
- **Formato original:** Excel

## Herramientas utilizadas
- Excel
- Power Query
- Tablas dinámicas
- Fórmulas (SUMA, PROMEDIO, MAX, BUSCARX)

## Limpieza y preparación de datos
La limpieza de datos se realizó en Power Query, incluyendo:
- Eliminación de columnas innecesarias.
- Corrección de encabezados con cabeceras múltiples.
- Renombrado de columnas para mayor claridad y consistencia.
- Conversión de columnas de participación (“Part.”) a formato porcentaje.
- Carga final como tabla estructurada en Excel (`SNASPE_LOS_LAGOS`).

## Validación de datos
Se creó una hoja independiente de validaciones para asegurar la calidad de los datos:
- Verificación de 12 meses sin duplicados ni valores faltantes.
- Validación de totales anuales y promedios.
- Comprobación de coherencia de porcentajes

