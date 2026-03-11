# Proyecto: Análisis Exploratorio de Datos - ComercioYA

## Descripción
Este proyecto presenta un análisis exploratorio de datos (EDA) detallado sobre el comportamiento histórico de ventas de la empresa **ComercioYA**. El objetivo principal es identificar patrones de consumo y variables clave que influyen en el ticket promedio, permitiendo fundamentar decisiones estratégicas de negocio.

## Etapas del Proyecto
1. **Limpieza de datos:** Tratamiento de valores nulos, duplicados y detección/eliminación de outliers mediante el rango intercuartílico (IQR).
2. **Estadística descriptiva:** Cálculo de medidas de tendencia central y dispersión para comprender la variabilidad de las ventas.
3. **Correlación:** Identificación de variables con mayor impacto mediante mapas de calor (heatmap).
4. **Regresión:** Modelado lineal (OLS) para predecir el comportamiento del cliente y evaluar la significancia de las variables.
5. **Visualización:** Análisis profundo mediante librerías Seaborn y Matplotlib, incluyendo gráficos de dispersión, distribución y análisis temporal.

## Insights Principales
* **Correlación:** Existe una relación positiva entre el ingreso mensual del cliente y el total de compra.
* **Factores influyentes:** La cantidad de productos y el precio unitario tienen un impacto directo y significativo en el total de la venta.
* **Patrones temporales:** La distribución de ventas presenta variaciones mensuales, lo que indica cambios estacionales en la demanda.
* **Calidad de datos:** La presencia de valores atípicos (outliers) fue gestionada para evitar sesgos en el promedio general, revelando una distribución asimétrica hacia la derecha.

## Recomendaciones Estratégicas
* **Segmentación:** Implementar campañas de marketing dirigidas específicamente a clientes con mayor ingreso mensual.
* **Ticket Promedio:** Promover productos de mayor valor unitario para maximizar los ingresos por transacción.
* **Fidelización:** Analizar los perfiles de clientes con compras recurrentes de alto monto para desarrollar programas de lealtad.

## Tecnologías Utilizadas
* Python (Pandas, Numpy, Statsmodels, Scikit-learn)
* Matplotlib & Seaborn para la visualización de datos
* Google Colab (Desarrollo del cuaderno)
