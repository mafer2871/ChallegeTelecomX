# 📊 Análisis de Cancelación de Clientes – Telecom X

Este repositorio contiene un análisis exploratorio y descriptivo del comportamiento de cancelación de clientes (*churn*) en una empresa de telecomunicaciones ficticia: **Telecom X**. El objetivo principal es identificar los factores asociados a la pérdida de clientes y construir la base para un modelo predictivo y estrategias de retención.


## 🎯 Objetivo

- Analizar el perfil de los clientes que cancelan sus servicios.
- Identificar patrones relevantes por características demográficas, servicios contratados y métodos de pago.
- Realizar recomendaciones con base en las observaciones
---

## 📁 Contenido del Repositorio 

- telecomx.ipynb: El archivo de Google Colab que contiene el código Python completo y el informe final del análisis.
- README.md: Este archivo, que proporciona una descripción general del proyecto.
- Imagenes: Carpeta con los archivos de las gráficas realizadas.

---

##⚡ Cómo Ejecutar el Código 
Acceder al Notebook de Google Colab: Abre el archivo telecomx.ipynb en Google Colab.
Ejecutar las Celdas: Ejecuta las celdas de código secuencialmente en el notebook. Los resultados del análisis y las visualizaciones se mostrarán directamente en el notebook.

---

## 🧪 Tecnologías y Librerías Usadas

- **Python 3.10+**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 🔍 Principales Hallazgos

- La tasa de cancelación general es del **26.6%**.
- Los **adultos mayores (≥65 años)** cancelan en un **41.68%**.
- Clientes **sin pareja ni dependientes** presentan tasas superiores al 30%.
- El servicio de **internet por fibra óptica** tiene una tasa de cancelación del **41.89%**, la más alta.
- **Contratos mes a mes** muestran una evasión del **42.71%**.
- El método de pago con **cheque electrónico** se asocia con una tasa del **45.29%**.
- Clientes con **altos cargos mensuales y baja antigüedad** (menos de 2 años) cancelan más.

---

## 📈 Visualizaciones

Se generaron múltiples gráficos para visualizar la distribución de cancelaciones por variable categórica y continua. Algunos ejemplos incluyen:

- Cancelación por tipo de contrato.
- Cancelación por antiguedad
- Cancelación según método de pago.
- Comparaciones por servicio contratado (Teléfono, tipo internet).
- Segmentación demográfica (edad, estado civil, dependientes).

---

## 🚀 Próximos pasos

- Desarrollo de un modelo de **machine learning** para predecir la cancelación.
- Implementación de un sistema de **alertas tempranas** y **score de riesgo**.
- Diseño de **estrategias de retención personalizadas** por segmento de cliente.

---

## 📌 Créditos

Este análisis fue desarrollado por el equipo de analítica de datos como parte de un ejercicio práctico de churn prediction.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo [LICENSE](LICENSE) para más información.

---
