# Análisis de Evasión de Clientes: Telecom X

Este proyecto fue desarrollado como parte del desafío de Ciencia de Datos de Telecom X.
El objetivo principal es ayudar a la empresa a entender los factores que llevan a la evasión de clientes y desarrollar estrategias para reducir las cancelaciones y mejorar la retención.

A través del análisis de datos reales de clientes, categorías de servicios, información contractual y patrones de comportamiento, se identifican las fortalezas y debilidades de cada segmento para tomar una decisión informada.

## Objetivo

Identificar los factores clave que influyen en la evasión de clientes con base en:

• **Antigüedad del cliente** 📅  
• **Tipo de contrato contratado** 📋  
• **Servicios adicionales suscritos** 🔧  
• **Cargos mensuales y totales** 💰  
• **Método de pago utilizado** 💳  
• **Perfil demográfico del cliente** 👥  

## Herramientas utilizadas

• **Python** (en Google Colab)  
• **Pandas** para análisis de datos  
• **Matplotlib** y **Seaborn** para visualización  
• **Gráficos** como barras, pastel, dispersión y matrices de correlación  

## Secciones del análisis

### 1. Extracción y limpieza de datos
Se procesaron los datos desde API JSON, desanidando estructuras complejas y limpiando inconsistencias.

### 2. Exploración de datos
Se analizó la distribución de evasión y se identificaron patrones por variables demográficas y de servicios.

### 3. Análisis de variables categóricas
Se examinaron las tasas de evasión por tipo de contrato, servicios adicionales y métodos de pago.

### 4. Análisis de variables numéricas
Se compararon antigüedad, cargos mensuales y totales entre clientes que se van vs. se quedan.

### 5. Análisis de correlaciones
Se exploraron las relaciones entre variables y su impacto en la evasión de clientes.

### 6. Visualizaciones y patrones
Se crearon gráficos para identificar visualmente los factores de mayor impacto en el churn.

## Principales hallazgos

**Tasa de evasión identificada: 26.5%** ⚠️

• **Contratos month-to-month:** 42.7% de evasión  
• **Clientes nuevos (<18 meses):** Mayor riesgo de cancelación  
• **Sin servicios adicionales:** Significativamente mayor churn  
• **Cargos altos (>$70):** Mayor propensión a la evasión  
• **Electronic check:** Método de pago más inestable  

## Recomendación final

Después de analizar todos los datos, se recomienda que Telecom X enfoque sus estrategias de retención en:

• **Programa de retención temprana** 🎯  
• **Incentivos para contratos anuales** 📋  
• **Promoción de servicios adicionales** 🔧  
• **Optimización de precios** 💰  
• **Mejora en métodos de pago** 💳  

Esta estrategia permitirá reducir la evasión del 26.5% actual al 18-20% objetivo, generando un impacto económico positivo estimado de $1.8M anuales para el crecimiento del negocio.

## Archivos incluidos

• **telecom_churn_analysis.ipynb** → notebook con todo el análisis y visualizaciones  
• **README.md** → descripción general del proyecto  

## Autor

Proyecto realizado por **Fabiola Sepúlveda**  
Como parte del Challenge de Ciencia de Datos — Telecom X
