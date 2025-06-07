readme: |
  # 🌸 Análisis Exploratorio del Dataset de Iris

  Este proyecto realiza un análisis exploratorio básico del famoso dataset de Iris utilizando herramientas estándar de análisis de datos en Python. El objetivo es generar estadísticas descriptivas y visualizaciones que nos permitan comprender la distribución y relaciones entre las características del dataset.

  ---

  ## 📌 Descripción del dataset

  El dataset de Iris contiene 150 observaciones de flores, distribuidas en 3 especies: *Setosa*, *Versicolor* y *Virginica*. Cada muestra tiene 4 características:

  - Longitud del sépalo (`sepal length`)
  - Ancho del sépalo (`sepal width`)
  - Longitud del pétalo (`petal length`)
  - Ancho del pétalo (`petal width`)

  Este dataset es cargado desde `sklearn.datasets`.

  ---

  ## 🎯 Objetivos

  - Calcular estadísticas descriptivas generales.
  - Visualizar la distribución de cada variable mediante histogramas.
  - Detectar valores atípicos utilizando boxplots.
  - Explorar relaciones entre variables mediante pairplots y mapas de correlación.

  ---

  ## 🧰 Herramientas y librerías

  - Python 3.x
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - Jupyter Notebook

  ---

  ## 🗂 Estructura del proyecto

iris-analysis/
│
├── data/
│ └── raw/ # Dataset iris en formato parquet
│
├── notebooks/
│ └── 01_eda_iris.ipynb # Análisis exploratorio completo
│
├── src/ # (opcional) Funciones auxiliares
│
├── requirements.txt
├── README.md


---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/iris-analysis.git
   cd iris-analysis
   ```

2. Crea y activa un entorno virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```

3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Ejecuta el notebook:
   ```bash
   jupyter notebook notebooks/01_eda_iris.ipynb
   ```

---

