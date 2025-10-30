# 📞 CallMeMaybe: The Case of Inefficient Operators  
### 🧠 Predictive Analysis of Contact Center Efficiency  

## 📘 Project Description  
This project analyzes the operational efficiency of a customer service center using real-world inspired performance metrics. The goal was to uncover hidden inefficiencies among operators — the silent productivity leaks draining satisfaction and revenue.  

The dataset includes indicators such as response time, resolution rate, call duration, and satisfaction level. Through data analysis, visualizations, and predictive modeling, this investigation shows how data becomes the detective in a workplace story.  

**Dataset:** Simulated Call Center Performance Data (3,000+ records, 15 features)  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  

---

## 🎯 Objectives  
- Identify operator traits or behaviors linked to inefficiency.  
- Quantify inefficiency and its root causes through data-driven analysis.  
- Provide actionable recommendations for operational improvement.  

---

## 🧩 Methodology  
**1. Data Cleaning and Preparation:** Handling missing satisfaction scores, normalization, and encoding categorical variables.  
**2. EDA:** Pattern detection by shift and department.  
**3. Hypothesis Testing:** ANOVA confirms differences in satisfaction (p=0.003).  
**4. Modeling:** Random Forest — accuracy 92.1%, F1-score (inefficient) 0.88.  
**5. Visualization:** Feature importance, heatmaps, and Pareto analysis.  

---

## 📊 Key Findings  
- Night shift operators had **17% lower resolution rates**.  
- Satisfaction dropped sharply after **8 minutes** of average call duration.  
- Workflow design was the main driver of inefficiency.  

---

## ⚙️ How to Run  

```bash
# Requirements
Python >= 3.8
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

**Execution steps:**  
1. Open `operadores_ineficaces_callmemaybe.ipynb`  
2. Execute cells in order to reproduce results.  

⏱️ Estimated runtime: 1–2 minutes.  

---

## 🚀 Future Improvements  
- Add NLP analysis on operator notes to detect tone and stress.  
- Develop a Power BI dashboard for real-time insights.  
- Implement time-series models to forecast inefficiency peaks.  

---

## 💼 Real-World Application  
This serves as an **operational intelligence framework** for customer service centers.  
It helps identify structural bottlenecks, reduce response times, and boost satisfaction.  

> Where management saw “lazy agents,” data revealed “systemic inefficiency.”

---

# 📞 CallMeMaybe: El Caso de los Operadores Ineficientes  
### 🕵️‍♂️ Análisis predictivo de eficiencia en centros de atención  

## 📘 Descripción del Proyecto  
Este proyecto analiza la eficiencia operativa de un centro de atención al cliente utilizando métricas inspiradas en datos reales. El objetivo fue descubrir ineficiencias ocultas entre operadores: pequeñas fugas de productividad que afectan la satisfacción del cliente y los ingresos.  

El dataset incluye indicadores como tiempo de respuesta, tasa de resolución, duración de llamada y nivel de satisfacción. A través de análisis de datos, visualizaciones y modelos predictivos, esta investigación muestra cómo los datos se convierten en el detective de una historia laboral.  

**Dataset:** Simulated Call Center Performance Data (3,000+ registros, 15 variables)  
**Herramientas:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  

---

## 🎯 Objetivos  
- Identificar los comportamientos o características que explican el bajo rendimiento de los operadores.  
- Cuantificar la ineficiencia y sus causas mediante análisis estadístico y modelos predictivos.  
- Generar recomendaciones accionables para optimizar la operación.  

---

## 🧩 Metodología  
**1. Carga y limpieza de datos:** Tratamiento de valores faltantes, normalización y codificación de variables categóricas.  
**2. EDA:** Identificación de patrones por turno y departamento.  
**3. Pruebas de hipótesis:** ANOVA para diferencias de satisfacción.  
**4. Modelado:** Random Forest con accuracy del 92.1% y F1-score (ineficientes) de 0.88.  
**5. Visualización:** Importancia de variables, heatmaps y análisis de Pareto.  

---

## 📊 Resultados Clave  
- Los operadores del turno nocturno presentan una tasa de resolución **17% menor**.  
- La satisfacción cae drásticamente después de **8 minutos de llamada promedio**.  
- Las ineficiencias se deben más a la estructura operativa que al esfuerzo individual.  

---

## ⚙️ Cómo Ejecutar  

```bash
# Requisitos
Python >= 3.8
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

**Pasos de ejecución:**  
1. Abre el archivo `operadores_ineficaces_callmemaybe.ipynb`  
2. Ejecuta las celdas en orden para reproducir resultados.  

⏱️ Tiempo estimado de ejecución: 1–2 minutos.  

---

## 🚀 Mejoras Futuras  
- Integrar análisis de texto (NLP) para detectar tono emocional.  
- Crear dashboard en Power BI para seguimiento en tiempo real.  
- Modelos de series de tiempo para anticipar horas pico.  

---

## 💼 Aplicación en el Mundo Real  
Este análisis funciona como un **sistema de inteligencia operativa** para contact centers.  
Permite detectar cuellos de botella, reducir tiempos de respuesta y mejorar la satisfacción del cliente.  

> Donde la gerencia veía “agentes perezosos”, los datos revelaron “ineficiencias estructurales”.
```
