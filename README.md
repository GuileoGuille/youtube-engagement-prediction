# 📊 Predicción de Rendimiento y Retención en YouTube con Machine Learning

**Autor:** Guillermo Zapata  
**Industria:** Entretenimiento Digital, Animación y Videojuegos  

## 🎯 Resumen del Proyecto
En la industria de la animación y el contenido digital, producir un video es altamente costoso. Este proyecto utiliza algoritmos de Machine Learning para predecir los ingresos y la retención de audiencia de un video en YouTube basándose en métricas tempranas de interacción (CTR, retención, likes, etc.). El objetivo es pasar de una toma de decisiones basada en la intuición a estrategias predictivas impulsadas por datos (Data-Driven).

## 🗂️ Estructura de este Repositorio
En este repositorio encontrarás el ecosistema completo del proyecto:
* 💻 **`Proyecto Final Guillermo Zapata.ipynb`**: Notebook interactivo con todo el proceso de limpieza, EDA y entrenamiento del modelo.
* ⚙️ **`Proyecto Final Guillermo Zapata.py`**: Script de Python estructurado para ejecución directa.
* 📄 **`Informe Final Ciencia de Datos I - Guillermo Zapata.pdf`**: Documento técnico detallado con la justificación matemática y de negocio.
* 📊 **`Estrategia Predictiva para Canales de YouTube.pdf`**: Presentación ejecutiva enfocada en la toma de decisiones para stakeholders.
* 🗄️ **`youtube_channel_real_performance_analytics.csv`**: Dataset original utilizado para el entrenamiento.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Lenguaje:** Python
* **Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest Regressor)
* **Entorno:** Jupyter Notebook / Google Colab

## 📈 Hallazgos Clave (Insights) y Visualizaciones

### 1. La Retención es el Rey
El análisis de correlación demostró que el *Watch Time* impacta exponencialmente más en los ingresos que interacciones superficiales como los *Likes*.
![Mapa de Correlación](Mapa%20de%20Correlacion.png)

### 2. El Espejismo del Clickbait
Un CTR alto (una buena miniatura) no garantiza rentabilidad si el video no logra retener a la audiencia en los primeros 30 segundos. El algoritmo penaliza el clickbait sin retención.
![Relación CTR vs Vistas](Relacion%20entre%20el%20CTR.png)

### 3. El Efecto Pareto en los Ingresos
La distribución financiera tiene una marcada asimetría hacia la derecha: la inmensa mayoría de los videos generan retornos modestos, mientras que un grupo selecto de "outliers" virales captura la mayor rentabilidad.
![Distribución de Ingresos](Distribuccion%20entre%20los%20ingresos.png)

## 🚀 Cómo ejecutar este proyecto localmente

1. Clona este repositorio: 
```bash
git clone [https://github.com/GuileoGuille/prediccion-de-interaccion-de-youtube.git](https://github.com/GuileoGuille/prediccion-de-interaccion-de-youtube.git)
