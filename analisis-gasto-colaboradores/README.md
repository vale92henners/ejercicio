# Análisis de gasto y compensaciones de colaboradores

Proyecto académico (UDLA, Decisiones y Simulación) desarrollado en equipo con Python.

**Pregunta de negocio:** ¿dónde se concentra el gasto y qué áreas, ciudades y modalidades rinden mejor en una empresa de 350 colaboradores?

## Qué hice
1. **Limpieza:** eliminé 10 duplicados, normalicé texto, corregí typos y marqué como nulos datos imposibles (edades de −5 y 250 años, satisfacción sobre 10, ingresos de $15 millones).
2. **Análisis:** 15 preguntas de negocio en tres niveles: distribución por ciudad y estado, gasto por departamento, Pareto, segmentación por ingreso, ranking de evaluación y mapa de calor ciudad × modalidad.
3. **Entrega:** exportación del dataset limpio y un resumen comercial a Excel, con una hoja por tabla.

## Hallazgos principales
- Gasto mensual total: **$110,8 millones**; Ventas concentra el **23%**.
- Ingreso mensual promedio: **$1,32 millones**; la modalidad remota gana menos en 4 de 5 ciudades.
- Finanzas es el área mejor evaluada (**4,50** vs 4,01 de la empresa).
- La satisfacción no se relaciona con el gasto (**r = −0,007**).

## Herramientas
Python · pandas · NumPy · matplotlib · seaborn · Excel
