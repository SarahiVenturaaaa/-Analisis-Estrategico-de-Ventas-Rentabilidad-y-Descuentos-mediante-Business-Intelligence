# 📊 Retail Sales Business Intelligence Dashboard

# 🎯 Objetivos

Este dashboard fue diseñado para responder las siguientes preguntas de negocio:

- ¿Qué productos generan mayor rentabilidad?
- ¿Los productos con mayores ventas son realmente los más rentables?
- ¿Qué productos aportan mayor valor al negocio?
- ¿Qué productos destruyen valor a pesar de generar ingresos?
- ¿Qué nivel de descuento ofrece el mejor equilibrio entre ventas y rentabilidad?
- ¿Qué ciudades representan los mercados más rentables?

El objetivo es comprender el comportamiento del negocio desde diferentes perspectivas y proporcionar información que facilite la toma de decisiones, permitiendo priorizar productos, evaluar estrategias de descuento e identificar oportunidades de mejora.
---
👉 **Enlace del dashboard:**

**🔗 https://app.powerbi.com/groups/me/reports/cb8db6df-f5d4-4509-888c-b91c032b5f93/28b7735a506b3b39d831?experience=power-bi&bookmarkGuid=37caf93ef5f20d5e0d35**

---

# 📌 Descripción

Este proyecto presenta el desarrollo de un dashboard interactivo en **Power BI** orientado al análisis estratégico de ventas, rentabilidad, descuentos y desempeño geográfico utilizando el conjunto de datos **Superstore**.

Más allá de construir un panel de visualización, el objetivo fue desarrollar una herramienta de apoyo para la **toma de decisiones empresariales**, respondiendo preguntas relacionadas con el desempeño de los productos, la rentabilidad, las estrategias de descuento y la distribución geográfica de las ventas.

Previo al desarrollo del dashboard, se realizó una etapa completa de **Análisis Exploratorio de Datos (EDA)** y limpieza de datos utilizando **Python**, garantizando la calidad y consistencia de la información antes de su análisis en Power BI.

---

# 📊 Dashboard

El dashboard se divide en cuatro secciones principales.

---

## 📈 1. Product Performance Analysis

Esta sección proporciona una visión general del desempeño de los productos mediante indicadores clave de negocio (KPIs) y visualizaciones interactivas.

Incluye:

- Ventas Totales.
- Ganancias Totales.
- Margen de Ganancia (Profit Margin).
- Rentabilidad por producto.
- Volumen de ventas por producto.
- Comparación entre ventas y ganancias.

Además, incorpora filtros dinámicos por categoría y producto, permitiendo explorar el comportamiento individual de cada grupo de productos.

Esta sección facilita identificar rápidamente qué productos generan mayores ventas, cuáles producen mayor utilidad y cuáles presentan un menor nivel de rentabilidad.
<p align="center">
<img src="´Product_perfomance_analysis.png" width="900">
</p>
---

## 📊 2. Product Contribution Analysis

Las ventas elevadas no siempre implican una mayor rentabilidad. Por ello, esta sección incorpora indicadores que permiten evaluar la verdadera contribución de cada producto al negocio, tanto en porcentaje como en valor monetario.

Para ello se desarrollaron las siguientes métricas:

- Contribution Sales by Product (%)
- Contribution Sales by Product ($)
- Contribution Profit by Product (%)
- Contribution Profit by Product ($)
- Profit Margin (%)

### Este análisis permitió identificar:

- Productos con alto volumen de ventas pero baja rentabilidad.
- Productos altamente rentables con un menor volumen de ventas.
- Productos que generan ingresos, pero presentan utilidades negativas y destruyen valor para la empresa.

Este análisis demuestra que un alto volumen de ventas no implica necesariamente una mayor contribución a la utilidad, permitiendo identificar qué productos aportan realmente valor al negocio.

---

## 💰 3. Impact of Discount per Product

Una de las principales aportaciones del proyecto consiste en analizar el equilibrio entre ventas y rentabilidad bajo diferentes niveles de descuento.

Para ello se compararon distintos niveles de descuento sin asumir relaciones causales, identificando aquellos que incrementan la participación en las ventas sin deteriorar significativamente la rentabilidad.

El objetivo es responder la siguiente pregunta:

> **¿Qué nivel de descuento ofrece el mejor equilibrio entre participación en ventas y rentabilidad para cada producto?**

Para ello se desarrollaron los siguientes indicadores para cada producto:

- Sales (%)
- Profit (%)
- Profit Margin (%)
- Delta Sales (diferencia entre la participación de las ventas sin descuento y la participación obtenida al aplicar un determinado nivel de descuento).
- Delta Profit Margin (diferencia entre el margen de ganancia sin descuento y el margen obtenido después de aplicar un determinado nivel de descuento).

Este análisis permitió identificar productos cuyos descuentos incrementan considerablemente la participación en ventas manteniendo una rentabilidad aceptable, así como aquellos donde los descuentos reducen significativamente el margen de ganancia.

---

## 🌎 4. Geographical Performance Analysis

Esta sección explora el desempeño comercial desde una perspectiva geográfica con el objetivo de identificar los mercados más rentables y detectar ciudades con oportunidades de mejora.

Incluye las siguientes visualizaciones:

- Visualización de las 15 ciudades con mayores descuentos aplicados y aquellas con mayores ventas.
- Tabla comparativa con las ventas, descuentos y ganancias de cada ciudad.
- Mapa interactivo donde el tamaño de cada burbuja representa el margen de ganancia de cada ciudad.

Además, al posicionar el cursor sobre una ciudad se muestran indicadores adicionales mediante tooltips, incluyendo:

- Ventas.
- Ganancias.
- Descuento promedio aplicado.
- Margen de ganancia.

---

# 🐍 Exploratory Data Analysis (Python)

Antes de desarrollar el dashboard se realizó una etapa completa de limpieza y análisis exploratorio de datos utilizando Python.

Las actividades desarrolladas incluyen:

- Conversión de tipos de datos.
- Identificación de valores faltantes.
- Detección de registros duplicados.
- Análisis de la distribución de variables numéricas y categóricas.
- Histogramas interactivos.
- Boxplots interactivos.
- Pairplots.
- Matriz de correlación.
- Análisis de variables categóricas.

Esta etapa permitió garantizar la calidad de la información antes de construir el dashboard y comprender el comportamiento de las variables previo al análisis de negocio.
