# Análisis de Mercado y Estrategia de Marketing - Videojuegos 🎮

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

> Proyecto desarrollado como parte del bootcamp de Data Analytics 
> de TripleTen (2026). Dataset real de ~16,000 registros de ventas 
> globales de videojuegos (1980-2016).

---

## 1. Problema de negocio

Una tienda global de videojuegos (Ice Store) necesitaba definir 
qué plataformas, géneros y regiones priorizar para sus campañas 
de marketing de 2017. Tenían datos históricos de ventas pero sin 
estructura analítica para extraer decisiones concretas.

**Pregunta clave:** ¿Qué factores determinan el éxito comercial 
de un videojuego y dónde debe invertir la empresa para maximizar 
el retorno?

---

## 2. Metodología

**Paso 1 - Carga y revisión de datos**
- Dataset: `games.csv` con ~16,000 registros (1980-2016)
- Variables: plataforma, género, región (NA, EU, JP, otros), 
  ventas globales, reseñas de críticos y usuarios

**Paso 2 - Limpieza y preparación**
- Detección y manejo de valores faltantes
- Normalización de nombres de plataformas y géneros
- Conversión de tipos de datos y filtrado de registros 
  inconsistentes

**Paso 3 - Análisis exploratorio (EDA)**
- Evolución del mercado por año (1980-2016)
- Ciclo de vida de plataformas: duración promedio de 8-12 años
- Distribución de ventas globales por plataforma y género
- Comparación regional: NA, EU y JP

**Paso 4 - Análisis de correlaciones**
- Relación entre reseñas de críticos y ventas globales
- Relación entre reseñas de usuarios y ventas
- Análisis por plataforma para detectar diferencias

**Paso 5 - Validación estadística**
- Pruebas de hipótesis (t-test, p-valores) sobre diferencias 
  de comportamiento entre regiones y plataformas

---

## 3. Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| Python | Lenguaje principal de análisis |
| Pandas | Manipulación y limpieza de datos |
| Matplotlib / Seaborn | Visualización de tendencias y correlaciones |
| SciPy | Pruebas de hipótesis estadísticas |
| Jupyter Notebook | Entorno de desarrollo y documentación |

---

## 4. Hallazgos principales

**Correlación reseñas → ventas:**
- Reseñas de críticos: correlación moderada-alta con ventas 
  globales **(r = 0.58)**
- Reseñas de usuarios: correlación más débil - las críticas 
  profesionales son el mejor predictor disponible

**Plataformas líderes (datos al cierre del análisis):**
- PS4 y Xbox One dominaban el mercado activo
- PS3 y Xbox 360 en declive pero con actividad residual
- Ciclo de vida promedio: 8-12 años antes de caída significativa

**Diferencias regionales claras:**

| Región | Géneros más vendidos | Plataformas preferidas |
|---|---|---|
| Norteamérica | Action, Shooter, Sports | Xbox One, PS4 |
| Europa | Action, Shooter, Sports | PS4, PC |
| Japón | Role-Playing, Action | 3DS, PS3/PS4 |

**Tendencia del mercado:**
- Pico de lanzamientos entre 2008-2011
- Post-2011: menos títulos pero mayor selectividad del mercado
- Mercado más competitivo y exigente hacia 2016

---

## 5. Recomendaciones de negocio

**- Concentrar presupuesto de marketing 2017 en PS4 y Xbox One** 
para NA y EU - plataformas activas con mayor base de usuarios.

**- Estrategia diferenciada para Japón** - géneros RPG y 
plataformas portátiles (3DS) tienen comportamiento radicalmente 
distinto al mercado occidental.

**- Usar score de críticos como filtro de calidad** antes de 
decidir inversión en un título - correlación r=0.58 lo convierte 
en el indicador más confiable disponible.

 **- Evitar inversión en plataformas en declive** - el ciclo de 
vida de 8-12 años indica cuándo una plataforma está perdiendo 
relevancia comercial.

**- Aprovechar ventanas de lanzamiento** de nuevas plataformas - 
los datos muestran picos de ventas asociados a nuevas generaciones 
de consolas.

---

## 6. Cómo ejecutar el proyecto

```bash
# 1. Clona el repositorio
git clone https://github.com/XNico619X/Analisis_mercado_estrategia_marketing_Videojuegos

# 2. Instala las dependencias
pip install pandas matplotlib seaborn scipy jupyter

# 3. Abre el notebook
jupyter notebook videojuegos.ipynb
```

>  El archivo `games.csv` debe estar en la misma carpeta 
> que el notebook para que el análisis funcione correctamente.

---

## 7. Estructura del repositorio
Analisis_mercado_estrategia_marketing_Videojuegos

- videojuegos.ipynb # Análisis completo y visualizaciones
- games.csv # Dataset original de ventas globales
- README.md # Este archivo


##  Autor

**Nicolás Espinosa Bedoya** - Data Analyst  
 [Portafolio](https://xnico619x.github.io) · 
 [LinkedIn](https://www.linkedin.com/in/nicolas-espinosa-bedoya-data-analyst) · 
 inge.nicoespi@gmail.com
