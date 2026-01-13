# Análisis Estadístico del Mercado de Videojuegos

**Proyecto Final – Estadística (Curso 2025–2026)**  
Facultad de Matemática y Computación (MATCOM)  
Universidad de La Habana

---

## 📌 Descripción general

Este repositorio contiene el desarrollo completo del **Proyecto Final de la asignatura Estadística**, cuyo objetivo es aplicar técnicas estadísticas descriptivas e inferenciales para analizar el mercado de los videojuegos a partir de datos reales.

El estudio se basa en el conjunto de datos **_Video Game Sales with Ratings_**, obtenido de la plataforma Kaggle, el cual combina información sobre ventas regionales y globales de videojuegos con valoraciones de críticos y usuarios. A partir de estos datos, se formulan preguntas de investigación y se aplican diversas técnicas estadísticas para extraer conclusiones fundamentadas.

---

## 🎯 Objetivos del proyecto

- Realizar un análisis exploratorio riguroso de un conjunto de datos real.
- Formular preguntas de investigación relevantes desde el punto de vista estadístico.
- Aplicar técnicas estadísticas vistas en el curso, tales como:
  - Pruebas de hipótesis
  - Regresión lineal múltiple
  - Análisis de Componentes Principales (PCA)
  - Clustering (K-Means)
- Interpretar los resultados obtenidos en el contexto del problema.
- Comunicar los hallazgos de forma clara, estructurada y profesional.

---

## ❓ Preguntas de investigación

1. **¿Existen diferencias estadísticamente significativas en las ventas globales de videojuegos entre los distintos géneros?**  
   → Pruebas de hipótesis (ANOVA / Kruskal–Wallis)

2. **¿En qué medida las valoraciones de críticos y usuarios explican las ventas globales de los videojuegos?**  
   → Regresión lineal múltiple

3. **¿Es posible identificar perfiles de videojuegos con características similares de ventas y valoraciones mediante técnicas multivariantes?**  
   → PCA + Clustering (K-Means)

Las preguntas están formuladas de manera progresiva, de modo que cada análisis motiva el siguiente, manteniendo un hilo narrativo coherente a lo largo del proyecto.

---

## 📊 Dataset utilizado

- **Nombre:** Video Game Sales with Ratings
- **Fuente:** Kaggle
- **Autor:** rush4ratio
- **Archivo principal:** `Video_Games_Sales_as_at_22_Dec_2016.csv`

### Variables principales

- Ventas regionales y globales:  
  `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`
- Valoraciones:  
  `Critic_Score`, `User_Score`
- Número de reseñas:  
  `Critic_Count`, `User_Count`
- Variables categóricas:  
  `Genre`, `Platform`, `Publisher`, `Rating`

---

## 🗂️ Estructura del repositorio

```bash
.
├── notebook/
│ └── proyecto_estadistica_videojuegos.ipynb
├── data/
│ └── Video_Games_Sales_as_at_22_Dec_2016.csv
├── figures/
│ └── (gráficos generados durante el análisis)
├── README.md
```

El notebook contiene todo el flujo del análisis: carga de datos, EDA, preparación, aplicación de métodos estadísticos y conclusiones

## 🛠️ Tecnologías y librerías utilizadas

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels
- scikit-learn

## ▶️ Ejecución del proyecto

1. Clonar el repositorio desde GitHub.
2. Instalar las dependencias necesarias.
3. Ejecutar Jupyter Notebook.
4. Abrir el archivo `proyecto_estadistica_videojuegos.ipynb` ubicado en la carpeta `notebook`.

El notebook está diseñado para ejecutarse de arriba abajo sin errores.

## 📌 Resultados principales

- Se identifican diferencias estadísticamente significativas en las ventas globales según el género del videojuego.
- Las valoraciones de críticos y usuarios muestran una influencia relevante, aunque no determinante, sobre el desempeño comercial.
- El análisis multivariante permitió identificar perfiles diferenciados de videojuegos en función de sus ventas y su recepción crítica.

## ⚠️ Limitaciones

- Presencia de valores faltantes en algunas variables.
- Ausencia de información sobre factores externos como marketing o presupuesto.
- Análisis basado en datos históricos.

## 👥 Autores

Sheila Roque Alemán / Equipo #18

## 📚 Contexto académico

Este proyecto fue realizado como parte de la evaluación final de la asignatura Estadística del programa de Ciencia de la Computación en la Universidad de La Habana (MATCOM).
