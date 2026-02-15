# 🧹 Data Cleaning & Preprocessing: CIS Survey

<div align="left">
  <img src="https://www.r-project.org/logo/Rlogo.svg" height="50" alt="R Logo" style="margin-right: 25px;"/>
  <img src="https://tidyverse.tidyverse.org/logo.png" height="50" alt="Tidyverse Logo" />
</div>
<br/>

**Subject:** Data Cleaning / Depuración de Datos


**Tools:** RStudio, Quarto, MICE, LOF Algorithm


**Focus:** Data Quality, Outlier Detection, Imputation

## 👥 Authors
Project developed by:
* **Pablo Galarón Mateo**
* **Hugo Alonso**
* **Gonzalo Blanca**
* **Raúl Palomo**

---

This project focuses on the **data cleaning and preparation phase**, which is crucial before any statistical modeling. We used a dataset from the **CIS (Center for Sociological Research)** Study nº 3428 to practice advanced cleaning techniques.

The goal was to transform raw, noisy data into a high-quality dataset ready for analysis.

### 🛠️ What we did
* **Data Auditing:** Identified initial errors in variables like "Hours dedicated to housework" and "Childcare".
* **Outlier Detection:** Used the **Tukey method** for univariate analysis and the **Local Outlier Factor (LOF)** algorithm for multivariate detection.
* **Missing Data (NAs):** Analyzed missingness patterns (MCAR/MAR). We applied **Simple Imputation** (Mean/Mode) for variables with low missingness and **Multiple Imputation by Chained Equations (MICE)** for complex cases.
* **Normalization:** Standardized scales and handled categorical levels (factors) for consistent analysis.

### 💡 Key Technical Skills
* **LOF Algorithm:** Identifying observations that are "unusual" in combination with others.
* **MICE:** Creating multiple "complete" datasets to ensure the statistical validity of the imputed values.
* **R Programming:** Developed custom functions (e.g., `Funcion_atipicos.R`) to automate the process.

### 📂 Files in this repo
* `📊 entrega_grupal.html`: The final technical report explaining the whole cleaning process.
* `📝 entrega_grupal.qmd`: Quarto source code.
* `⚙️ Funcion_atipicos.R`: A custom R function created to detect and plot outliers.
* `📂 data/`: Contains the raw and the final cleaned datasets (`base_depurada_mice.csv`).

---

Este proyecto se centra en la **fase de limpieza y preparación de datos**, crucial antes de cualquier modelado estadístico. Utilizamos un conjunto de datos del **CIS (Estudio nº 3428)** para practicar técnicas avanzadas de depuración.

El objetivo fue transformar datos brutos y con errores en un dataset de alta calidad listo para el análisis.

### 🛠️ Qué hicimos
* **Auditoría de Datos:** Identificamos errores iniciales en variables como "Horas de tareas del hogar" y "Cuidado de hijos".
* **Detección de Atípicos:** Usamos el **método de Tukey** para el análisis univariante y el algoritmo **LOF (Local Outlier Factor)** para la detección multivariante.
* **Datos Ausentes (NAs):** Analizamos los patrones de ausencia (MCAR/MAR). Aplicamos **Imputación Simple** (Media/Moda) y **Imputación Múltiple (MICE)** para los casos más complejos.
* **Normalización:** Estandarizamos escalas y gestionamos niveles de variables categóricas (factores).

### 💡 Habilidades Técnicas Clave
* **Algoritmo LOF:** Identificación de observaciones que son "raras" al combinarse con otras.
* **MICE:** Creación de múltiples datasets "completos" para asegurar la validez estadística de los datos inventados.
* **Programación en R:** Desarrollamos funciones propias (como `Funcion_atipicos.R`) para automatizar el proceso.

### 📂 Archivos en este repo
* `📊 entrega_grupal.html`: Informe técnico final con todo el proceso de limpieza.
* `📝 entrega_grupal.qmd`: Código fuente en Quarto.
* `⚙️ Funcion_atipicos.R`: Función de R personalizada para detectar y graficar atípicos.
* `📂 data/`: Contiene los datos originales y el dataset final depurado (`base_depurada_mice.csv`).
