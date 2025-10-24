![image](./data/gs.jpg)

# Análisis Exploratorio de Datos (EDA) - La Generación Perdida de 1990

## Objetivo
Este proyecto tiene como finalidad realizar un **Análisis Exploratorio de Datos (EDA)** sobre el rendimiento de los principales tenistas masculinos del circuito ATP, con especial enfoque en la **Generación de los 90** y en los integrantes del **Big 3**: **Roger Federer, Rafael Nadal y Novak Djokovic**.  
El objetivo es **identificar patrones de rendimiento, dominio por superficie y evolución histórica en los torneos de Grand Slam**, utilizando técnicas de análisis y visualización de datos en Python.

---

## Herramientas utilizadas
- **Python 3.11**
- **Pandas** → Limpieza, filtrado, agregación y manipulación de datos.  
- **NumPy** → Operaciones vectorizadas y cálculos estadísticos.  
- **Matplotlib / Seaborn** → Visualización gráfica de tendencias, comparaciones y distribuciones.  
- **Jupyter Notebook** → Entorno interactivo para el desarrollo del análisis.

---

## Datasets

**URL 1 - KAGGLE**  
https://www.kaggle.com/datasets/sijovm/atpdata  
**URL 2 - KAGGLE**  
https://github.com/JeffSackmann/tennis_atp  
**URL 3 - KAGGLE**  
https://www.kaggle.com/datasets/dissfya/atp-tennis-2000-2023daily-pull  

---

## Proceso del análisis
1. **Carga y exploración del dataset:** identificación de columnas clave (torneo, jugador, año, superficie, resultado).  
2. **Limpieza de datos:** tratamiento de valores nulos, estandarización de nombres y filtrado de jugadores relevantes.  
3. **Transformaciones y agregaciones:** uso de `groupby()`, `value_counts()`, `pivot_table()` y filtros booleanos para obtener métricas de victorias, finales y títulos.  
4. **Visualización:** creación de gráficos comparativos para analizar rendimiento por jugador, año y superficie.  
5. **Análisis focalizado:** comparación de número de títulos, finales y dominio por superficie entre distintas décadas.

---

## Principales hallazgos
- **Novak Djokovic** se posiciona como el jugador más dominante en número total de Grand Slams ganados.  
- **Rafael Nadal** muestra un rendimiento extraordinario en **superficie de tierra batida**, especialmente en Roland Garros.  
- **Roger Federer** mantiene un desempeño más equilibrado, destacando en **césped**.  
- Las visualizaciones permiten observar cómo el dominio de los Big 3 se alterna según la superficie y la etapa del torneo.

---

## Conclusión
El análisis confirma que el **Big 3 ha redefinido la historia del tenis moderno**, monopolizando la mayoría de los Grand Slams desde comienzos de los 2000, y la generación de 1990 tuvo que luchar contra ello.  
La exploración de datos permitió **identificar tendencias de rendimiento, evolución por año y dominio por superficie**, demostrando el valor del análisis exploratorio en el deporte como herramienta para comprender patrones competitivos y desempeño histórico.

---

## 📂 Estructura del proyecto
```
eda-tenis/
│
├── data/                     # Archivos de datos (datasets CSV, imágenes, etc.)
│   ├── atp_matches.csv
│   ├── players.csv
│   └── gs.jpg
│
├── notebooks/                # Jupyter Notebooks con el desarrollo del análisis
│   ├── 01_exploracion.ipynb
│   ├── 02_limpieza.ipynb
│   └── 03_visualizaciones.ipynb
│
├── src/                      # Scripts de Python reutilizables (funciones auxiliares)
│   ├── limpieza.py
│   ├── analisis.py
│   └── visualizaciones.py
│
├── outputs/                  # Gráficos, tablas y resultados generados
│   └── resumen_final.png
│
├── README.md                 # Descripción general del proyecto
└── requirements.txt          # Dependencias del entorno de Python
```

---

## 📚 Autor
Proyecto realizado por **Ignacio Díaz** como práctica de análisis exploratorio de datos en Python.
