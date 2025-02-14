# Análisis del Embudo de Ventas y Evaluación de un Test A/A/B en una Aplicación de Productos Alimenticios

## Contexto
En una empresa emergente que vende productos alimenticios a través de una aplicación móvil, comprender el comportamiento del usuario es clave para mejorar la conversión y la experiencia de compra. Este proyecto tiene como objetivo analizar el flujo de usuarios a lo largo del embudo de ventas y evaluar los resultados de un test A/A/B, que compara la percepción y el impacto de un cambio en las fuentes tipográficas de la aplicación.

## Herramientas Utilizadas
- **Python:** Para la manipulación y análisis de datos.
- **Pandas y NumPy:** Para la limpieza y estructuración de la información.
- **Matplotlib y Seaborn:** Para generar visualizaciones que faciliten el análisis de tendencias.
- **Scipy y Statsmodels:** Para la realización de pruebas estadísticas en el test A/A/B.
- **Dataset:** Registros de interacción de los usuarios con la aplicación, incluyendo eventos dentro del embudo de ventas y su asignación a los grupos de prueba.

## Análisis Realizado
**1. Análisis del Embudo de Ventas**
El embudo de ventas permite evaluar cómo los usuarios avanzan a través de diferentes etapas hasta la compra final. Este análisis busca responder preguntas clave como:

- ¿Cuántos usuarios completan el proceso de compra?
- ¿En qué etapas ocurre la mayor cantidad de abandonos?
- ¿Existen cuellos de botella que puedan optimizarse?
Para ello, se calcularon las tasas de conversión en cada paso del embudo y se identificaron los puntos de mayor fricción dentro del proceso.

**2. Evaluación del Test A/A/B**
El test A/A/B se diseñó para evaluar el impacto de un cambio en la fuente tipográfica de la aplicación. Se crearon tres grupos de usuarios:

- Grupo A1 y Grupo A2 (Control): Continuaron viendo la aplicación con las fuentes antiguas.
- Grupo B (Prueba): Recibió la aplicación con las nuevas fuentes.
El propósito de incluir dos grupos de control (A1 y A2) es validar que no haya diferencias significativas entre ellos. Si existen variaciones inesperadas, podrían indicar la presencia de factores ocultos que distorsionen los resultados.

Se analizaron métricas como:

- La tasa de conversión en cada grupo.
- La diferencia en la tasa de abandono entre los grupos.
- Pruebas estadísticas para determinar si los cambios en las fuentes impactaron significativamente la interacción del usuario.

## Resultados y Hallazgos
- **Embudo de Ventas:** Se identificaron etapas críticas donde la mayoría de los usuarios abandonaban la compra, permitiendo definir estrategias para mejorar la retención.
- **Test A/A/B:**
- No se encontraron diferencias significativas entre los grupos de control (A1 y A2), validando la confiabilidad del experimento.
- Al comparar el grupo B con los grupos de control, se determinó si el cambio en las fuentes afectó positiva o negativamente la conversión y la experiencia del usuario.

## Conclusiones
Este análisis proporciona información valiosa para mejorar la conversión dentro de la aplicación. Los hallazgos del embudo de ventas permiten enfocar esfuerzos en las etapas con mayor abandono, mientras que los resultados del test A/A/B ayudan a tomar decisiones informadas sobre el diseño visual de la aplicación.

En futuras iteraciones, se podrían realizar pruebas adicionales con otros elementos visuales, como colores o disposición de botones, para seguir optimizando la experiencia del usuario y la efectividad del proceso de compra.
