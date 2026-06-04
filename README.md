# Análisis de Mercado y Estrategia de Marketing para Videojuegos

## 1. Descripción del proyecto/problema que se resolvió
Este proyecto analiza datos históricos de ventas de videojuegos (1980–2016) para ayudar a una tienda global a tomar decisiones estratégicas de marketing en 2017. El objetivo principal fue identificar qué plataformas, géneros y regiones ofrecían mayor potencial de ventas, así como extraer patrones de comportamiento del mercado que permitan orientar inversiones, promociones y selecciones de catálogo.

## 2. Metodología: cómo se resolvió
1. Recolección y revisión de datos:
   - Se cargó el archivo `games.csv` con registros históricos de videojuegos.
   - Se inspeccionaron los datos para entender sus columnas, tipos de variables y calidad general.
2. Limpieza y preparación:
   - Se detectaron y manejaron valores faltantes o inconsistentes.
   - Se normalizaron nombres de plataformas, géneros y regiones para evitar duplicados.
3. Análisis exploratorio:
   - Se calcularon métricas clave como ventas globales, ventas por región y distribución de géneros.
   - Se identificaron tendencias temporales, plataformas populares y diferencias en comportamiento por región.
4. Modelado de insights:
   - Se comparó el desempeño de plataformas y géneros en las principales regiones (América del Norte, Europa, Japón, etc.).
   - Se priorizaron segmentos con mayor volumen de ventas y crecimiento sostenible.
5. Síntesis de resultados:
   - Se extrajeron conclusiones directas para estrategia de marketing y recomendaciones prácticas.

## 3. Herramientas usadas
- Python
- Jupyter Notebook (`videojuegos.ipynb`)
- Pandas para manejo y análisis de datos
- Matplotlib/Seaborn para visualización de tendencias
- Exploración de datos en `videojuegos.ipynb`
- Archivo CSV: `games.csv`

## 4. ¿Qué se descubrió?
- Las plataformas con mayores ventas históricas son aquellas que dominaban el mercado en el periodo analizado, lo que sugiere priorizar consolas consolidadas.
- Los géneros más vendidos presentaron diferencias claras por región: algunos géneros rindieron mejor en América del Norte, mientras otros tenían una mayor aceptación en Japón o Europa.
- Las ventas globales crecieron en ciertos años clave, evidenciando ventanas de oportunidad para campañas de lanzamiento asociadas a nuevas plataformas.
- Hubo un conjunto de plataformas y géneros con bajo rendimiento relativo que probablemente sean menos rentables para la estrategia de marketing de 2017.

## 5. Implicaciones para la empresa o recomendaciones para el negocio
- Priorizar campañas de marketing en las plataformas con mayor volumen de ventas histórico y con mejor proyección a corto plazo.
- Enfocar promociones de géneros exitosos en las regiones donde tienen mayor aceptación y adaptar el mensaje según el comportamiento regional.
- Reservar inversión publicitaria para títulos compatibles con las plataformas y regiones de mayor retorno esperado.
- Evitar invertir excesivamente en segmentos de bajo rendimiento a menos que se disponga de una propuesta de valor diferencial clara.
- Utilizar los hallazgos como base para futuras decisiones de catálogo y posicionamiento de productos, destinando recursos a oportunidades de mercado identificadas en los datos.

## Archivos del proyecto
- `games.csv`: datos originales de ventas de videojuegos.
- `videojuegos.ipynb`: análisis exploratorio y visualizaciones.
- `README.md`: resumen del proyecto, metodología y conclusiones.
