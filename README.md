# 📊 Análisis para Tienda Online

En este proyecto se realiza un análisis de hipótesis para el aumento de ingresos en una tienda online, mediante la priorización de hipótesis y la evaluación de un test A/B.

## 🎯 Objetivos

* Priorizar las hipótesis propuestas:
  * Aplicación del framework ICE (Impact, Confidence, Ease).
  * Aplicación del framework RICE (Reach, Impact, Confidence, Effort).

* Analizar los resultados del test A/B en:
  * Ingreso acumulado por grupo.
  * Número de pedidos por grupo.
  * Tamaño promedio del pedido y su diferencia relativa.
  * Tasa de conversión por grupo.
  * Identificación de anomalías.

* Análisis de significancia estadística en la tasa de conversión y el ticket promedio.

## 📅 Periodo Analizado
El test A/B tuvo una duración de un mes (del 01/08 al 31/08).

## 📈 Hallazgos Clave
* La diferencia en la tasa de conversión entre los grupos se estabilizó.
* El grupo A mostró una estabilización en el tamaño promedio del pedido.
* En el grupo B, el tamaño promedio aún no se estabiliza completamente debido a outliers, aunque muestra una tendencia a disminuir gradualmente.
* El análisis de significancia estadística indica una diferencia significativa en la tasa de conversión, pero no en el tamaño promedio del pedido.
* El grupo B presentó más visitas y más órdenes, pero no evidencia suficiente para considerarlo el grupo “ganador”.

## 🔍 Recomendaciones Estratégicas
Dar por concluida la prueba, analizando los factores que pudieron influir en la mejora de la tasa de conversión del grupo B, con el fin de evaluarlos y controlarlos en un próximo experimento.

## 🧪 Herramientas y Tecnología
* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* SciPy
* Statsmodels
* Jupyter Notebook