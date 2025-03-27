# 🎬 Sistema de Recomendación de Títulos de Netflix

### Autor: Affectus Jaureguizar
### Fecha: 27 de Marzo, 2025

---

## 📄 Descripción del Proyecto

Notebook interactivo que permite recomendar películas o series similares según título o género, utilizando similitud de contenido y filtros personalizados. Desarrollado con Python, Jupyter Notebook e ipywidgets sobre un dataset real de títulos disponibles en Netflix.

---

## 🧠 Objetivo del Proyecto

Construir un sistema de recomendación personalizado y flexible, que permita a los usuarios explorar contenido relacionado en la plataforma Netflix a partir de distintos criterios, facilitando la exploración temática, emocional o narrativa.

---

## 🛠️ Tecnologías Utilizadas

Python 3

Jupyter Notebook

Pandas · Scikit-learn · ipywidgets

Matplotlib · Seaborn

HTML (render simple en Jupyter)

---

## 🧬 Metodología

**Carga y limpieza de datos:**
Lectura del dataset original, identificación de nulos, normalización de títulos y creación de campos auxiliares (listed_in_esp, main_country, etc.).

**Análisis exploratorio (EDA):**
Visualizaciones con Seaborn y Matplotlib para comprender la distribución por tipo, país, rating y duración.

**Sistema de recomendación por título:**
Vectorización binaria de géneros (CountVectorizer) y cálculo de similitud de coseno entre títulos para encontrar los más similares.

**Sistema de recomendación por género:**
Búsqueda de títulos que contengan un género específico y recomendación aleatoria controlada.

**Interfaz interactiva con ipywidgets:**
El usuario puede elegir entre recomendar por título o por género, ajustar la cantidad de resultados, y filtrar por tipo de contenido (películas, series o ambos).

**Mensajes personalizados:**
En caso de que no existan suficientes resultados para los filtros seleccionados, se muestra una advertencia amigable.

--- 

## 🎯 Funcionalidades principales

-Recomendación por título o género

-Filtro por películas, series o ambos

-Control de cantidad de recomendaciones (3 a 15)

-Botón para actualizar resultados sin perder selección

-Mensajes claros cuando no hay resultados suficientes

---

## ▶️ Cómo ejecutar este proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/affec-ds/Netflix-Recommender-System.git

2. Abre el notebook:
   ```bash
   Jupyter Notebook > Sistema de Recomendación de Títulos de Netflix.ipynb

3. Ejecuta las celdas paso a paso para probar el sistema.

---

# ⚠️ Nota sobre visualización de widgets

Este proyecto usa ipywidgets, los cuales no se visualizan correctamente en GitHub.
Para una experiencia completa: 

🔗 Usa [nbviewer](https://nbviewer.org/) para previsualizar el notebook desde GitHub.

---

## 📩 Contacto
💼[Conectemos en LinkedIn](https://cl.linkedin.com/in/affectusjaureguizar)

💼[GitHub](https://github.com/affec-ds)
