# Telecom X - Análisis de Evasión de Clientes

## 📊 Descripción del proyecto

Este proyecto analiza la evasión de clientes (Churn) en la empresa Telecom X.  
El objetivo es identificar patrones y factores asociados a la cancelación del servicio mediante técnicas de análisis exploratorio de datos.

El análisis se realizó utilizando Python y bibliotecas como Pandas, Matplotlib y Seaborn.

---

## 🎯 Objetivos

- Comprender la distribución de la evasión de clientes.
- Identificar variables que puedan influir en el churn.
- Explorar patrones en variables categóricas y numéricas.
- Generar insights que ayuden a reducir la pérdida de clientes.

---

## 🛠 Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 🔎 Proceso de análisis

### 1. Extracción de datos
Los datos fueron obtenidos desde una API en formato JSON.

### 2. Transformación de datos
Se realizó la normalización de las estructuras anidadas del JSON para convertirlas en un DataFrame.

### 3. Limpieza de datos
Se verificaron valores nulos y se transformaron variables para permitir su análisis.

### 4. Análisis exploratorio
Se realizaron visualizaciones para identificar patrones de evasión según distintas variables como:

- Tipo de contrato
- Método de pago
- Género
- Gastos mensuales
- Tiempo como cliente

### 5. Análisis de correlación
Se evaluaron las relaciones entre variables numéricas mediante una matriz de correlación.

---

## 📈 Principales hallazgos

- Los clientes con contratos **mensuales** presentan mayor tasa de evasión.
- Los clientes con **mayores cargos mensuales** tienden a cancelar el servicio con mayor frecuencia.
- El tipo de contrato y método de pago muestran relación con la evasión de clientes.

---

## 💡 Recomendaciones

- Incentivar contratos de mayor duración para mejorar la retención de clientes.
- Analizar estrategias de precios para clientes con altos cargos mensuales.
- Implementar programas de fidelización para clientes con mayor riesgo de churn.

---

## 👩‍💻 Autor
Daniela H
Proyecto desarrollado como parte del desafío de análisis de datos del programa ONE.
