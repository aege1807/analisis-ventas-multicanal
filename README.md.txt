Análisis de desempeño comercial y rentabilidad

Ventas multicanal (2021–2024)

📌 Descripción del proyecto

Este proyecto analiza el desempeño comercial y la rentabilidad de las ventas realizadas entre 2021 y 2024, con el objetivo de identificar productos, categorías y canales que generan mayor valor económico para la empresa. El análisis se enfoca tanto en el volumen de ingresos como en la eficiencia financiera (margen de utilidad).

🎯 Objetivo

Evaluar la rentabilidad del portafolio de productos mediante el análisis de ingresos, costos y márgenes, y segmentarlos estratégicamente para apoyar la toma de decisiones comerciales y operativas.

🗂 Dataset

El dataset contiene registros de ventas con las siguientes variables principales:

fecha

producto

categoría

región

canal_venta

cantidad

precio_unitario

costo_unitario

descuento

cliente

El periodo de análisis abarca desde 2021 hasta 2024.

🧹 Limpieza y preparación de datos

Se realizaron las siguientes tareas:

Conversión de la columna fecha a formato datetime

Creación de variables temporales (año y mes)

Identificación y tratamiento de valores faltantes:

precio_unitario: imputación mediante media por producto

cantidad: imputación mediante mediana por producto

Validación de consistencia de los datos tras la imputación

Estas decisiones se tomaron para preservar la representatividad del dataset sin introducir sesgos significativos.

📐 Métricas calculadas

Se construyeron métricas financieras clave:

Ingresos:
precio_unitario × cantidad × (1 − descuento)

Costo total

Utilidad

Margen de utilidad ponderado

Estas métricas permiten evaluar tanto el impacto económico como la eficiencia de cada producto.

📈 Análisis realizado

Ranking de productos, categorías y canales por ingresos

Análisis de rentabilidad mediante margen de utilidad

Segmentación estratégica de productos usando una matriz:

Ingresos totales vs margen ponderado

Clasificación de productos en cuatro segmentos:

Estrella

Volumen

Nicho

Riesgo

🔍 Principales insights

Los productos electrónicos de uso común se posicionan como principales generadores de ingresos.

Existen productos con alto volumen pero baja rentabilidad, lo que sugiere oportunidades de optimización de costos o precios.

Algunos productos se encuentran cercanos a los umbrales de clasificación, indicando alta sensibilidad a cambios operativos.

La matriz estratégica facilita la identificación de prioridades comerciales y riesgos potenciales.

📊 Visualizaciones

El proyecto incluye visualizaciones clave, entre ellas:

Gráficos de ingresos por producto, categoría y canal

Matriz estratégica de productos (ingresos vs rentabilidad)

🛠 Herramientas utilizadas

Python

pandas

matplotlib

Jupyter Notebook (VS Code)

📌 Conclusiones

El análisis demuestra cómo el uso combinado de métricas financieras y segmentación estratégica permite obtener una visión integral del desempeño comercial. Este enfoque facilita la identificación de productos clave, oportunidades de mejora y riesgos, apoyando la toma de decisiones basada en datos.