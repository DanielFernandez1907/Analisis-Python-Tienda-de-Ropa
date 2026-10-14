# Análisis de datos en Python: tienda de ropa

Dos casos prácticos de análisis de datos y modelos predictivos en Python, realizados durante el Máster en Análisis de Datos para la Gestión Empresarial (UDIMA). Los datos son ficticios, de práctica.

## Contenido

- [Python-1.pdf](Python-1.pdf) – Caso práctico 1: importación y exploración de las cuatro tablas de la tienda.
- [Python-2.pdf](Python-2.pdf) – Caso práctico 2: análisis con gráficos y modelos predictivos.

## Caso práctico 2

**Análisis y visualización** (pandas, seaborn, matplotlib)
- Clientes por ciudad y género.
- Distribución de los métodos de pago.
- Relación entre precio y coste por categoría.
- Proveedores por país y riesgo de dependencia.
- Evolución mensual de las ventas.
- Ventas por ciudad y género.

**Modelos predictivos** (scikit-learn)
- Regresión lineal para predecir el importe de la venta (R² ≈ 0,11: las variables elegidas explican poco).
- Árbol de decisión para clasificar la venta en nivel bajo, medio o alto (exactitud ≈ 65 %, con desbalanceo de clases).

## Hallazgos principales

- La mayoría de las ventas se paga con tarjeta; el efectivo es casi inexistente.
- La relación precio-coste es positiva, lo que indica un margen de ganancia constante.
- Los productos están repartidos entre varios países proveedores, sin dependencia absoluta de ninguno.
- Las ventas crecen hasta febrero de 2025 y caen de forma notable después.

## Herramientas

Python, pandas, NumPy, matplotlib, seaborn y scikit-learn (Google Colab).

## Autor

Daniel Fernández Gutiérrez – [LinkedIn](https://www.linkedin.com/in/daniel-fernández-gutiérrez-3a7b542aa)
