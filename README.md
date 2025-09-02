# 📌 README – Proyecto AI Job Dataset  

## 📖 Descripción  
Este proyecto analiza un dataset de ofertas de empleo en el ámbito de **Inteligencia Artificial (IA)**.  
Se realiza un flujo completo de:  

- **ETL (Extract, Transform, Load)** → Limpieza y normalización de datos.  
- **EDA (Exploratory Data Analysis)** → Análisis exploratorio con visualizaciones.  
- **Generación de informes** en Word y PDF para documentación profesional.  

El objetivo es obtener una visión clara de los roles más demandados, rangos salariales, regiones más activas y relación entre experiencia y compensación.  

---

## ⚙️ Flujo del Proyecto  

### 1. **ETL Final**
- Lectura del dataset `ai_job_dataset.csv`.  
- Normalización de nombres de columnas.  
- Limpieza de valores nulos (relleno con medianas en numéricas y “desconocido” en categóricas).  
- Conversión de columnas de fecha a formato `datetime`.  
- Normalización de texto en variables categóricas.  
- Exportación a `ai_job_dataset_final.csv`.  

### 2. **EDA Final**
Se realizaron los siguientes análisis:  
- **Estructura del dataset** → dimensiones, tipos de variables.  
- **Valores faltantes** → gráfico de barras por columna.  
- **Distribución de variables numéricas** → histogramas y boxplots para outliers.  
- **Correlaciones** → heatmap de correlación entre variables numéricas.  
- **Análisis de categóricas** → conteo de categorías principales (roles, países, industrias).  

### 3. **Documentación**
- Se generó un **informe en Word (`Informe_EDA_AI_Jobs.docx`)** con texto explicativo y gráficos.  
- Se sugiere exportar el documento a **PDF** para entregar resultados.  

---

## 📊 Visualizaciones Incluidas  
- Valores nulos por columna.  
- Histogramas de variables numéricas.  
- Boxplots para detectar outliers.  
- Heatmap de correlaciones.  
- Gráficos de barras con top categorías en variables categóricas.  

Todas las visualizaciones se generaron con una **paleta verde-azulada** para mantener consistencia estética.  

---

## 🛠️ Tecnologías Usadas  
- **Python 3.13**  
- **Pandas** (manejo de datos)  
- **Matplotlib / Seaborn** (visualizaciones)  
- **Jupyter Notebook** (documentación y análisis)  
- **python-docx** (generación de informes en Word)  

---

## 📂 Estructura del Proyecto  
```
├── data/
│   ├── ai_job_dataset.csv          # Dataset original
│   ├── ai_job_dataset_final.csv    # Dataset limpio
├── notebooks/
│   ├── etl_final.ipynb             # Proceso ETL
│   ├── eda_final.ipynb             # Análisis EDA
├── reports/
│   ├── Informe_EDA_AI_Jobs.docx    # Informe con gráficos
│   └── Informe_EDA_AI_Jobs.pdf     # Informe exportado a PDF
├── README.md                       # Documentación del proyecto
```

---

## 🚀 Cómo Usar  
1. Clonar el repositorio.  
2. Instalar dependencias con:  
   ```bash
   pip install pandas matplotlib seaborn python-docx
   ```
3. Ejecutar los notebooks en `notebooks/` para reproducir el ETL y el EDA.  
4. Revisar el informe en `reports/` para el análisis final.  

---

## ✨ Conclusiones del Análisis  
- Existen roles predominantes en **machine learning, data science y NLP**.  
- Los salarios varían significativamente por región y experiencia.  
- La mayor concentración de empleos se encuentra en regiones específicas (ej. Norteamérica y Europa).  
- Las empresas demandan mayormente perfiles con **experiencia previa**.  

---

📌 Autor: *[Tu Nombre]*  
📅 Fecha: *2025*  
