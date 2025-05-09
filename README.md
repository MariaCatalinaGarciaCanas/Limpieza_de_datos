# 🧹 Limpieza de Datos - Precios de Casas en Melbourne

## 🌟 Introducción

¡Bienvenidos! En este proyecto, abordamos un desafío fundamental en la Ciencia de Datos: la **limpieza y preparación de un dataset real de precios de viviendas en Melbourne, Australia**. Descubre cómo convertimos datos brutos en un activo valioso, listo para el análisis y la construcción de modelos predictivos robustos.

## 🧩 Proceso y Enfoque

### 1. **Inspección inicial del dataset**
   - Análisis exploratorio inicial para **entender la estructura de los datos** y detectar posibles problemas como valores faltantes, tipos de datos incorrectos y posibles outliers.

### 2. **Manejo de valores nulos**
   - Se identificaron las columnas con **valores nulos**. Para aquellas con pocos nulos y variables importantes, se aplicó imputación. En columnas con una alta proporción de nulos o información redundante, se optó por la eliminación, justificando la decisión basada en el contexto de cada variable.

### 3. **Detección y manejo de outliers**
   - Identificación de **valores atípicos** en columnas clave como **precio** y **superficie** utilizando métodos visuales (boxplots) y estadísticos. Se aplicaron estrategias para mitigar su impacto en futuros análisis.

### 4. **Transformación de variables**
   - Algunas variables numéricas fueron **escaladas** para asegurar que tengan un rango similar, lo cual es beneficioso para ciertos algoritmos de machine learning.

### 5. **Codificación de variables categóricas**
   - Las variables categóricas fueron codificadas utilizando técnicas como one-hot encoding para convertirlas en un formato numérico que los modelos puedan procesar.

---

## 💻 Herramientas y Tecnologías

- **Lenguaje de programación**: Python
- **Librerías clave**:
    - Pandas: Manipulación y limpieza de datos.
    - NumPy: Cálculos numéricos.
    - Matplotlib y Seaborn: Visualización de datos para exploración y detección de outliers.
    - Scikit-learn: Preprocesamiento (escalado, codificación).

---

## 🎯 Objetivo

El objetivo principal de este proyecto es entregar un **dataset limpio y preprocesado** del mercado inmobiliario de Melbourne. Este conjunto de datos estará **optimizado para el desarrollo de modelos predictivos precisos**, como regresión lineal, árboles de decisión o redes neuronales, y servirá como una base sólida para futuros análisis exploratorios y de modelado.

---

## 🚀 Cómo empezar

1.  **Clona el repositorio:**

    ```bash
    git clone [https://github.com/TuUsuario/Limpieza-De-Datos-Melbourne.git](https://github.com/TuUsuario/Limpieza-De-Datos-Melbourne.git)
    ```

2.  **Navega al directorio del proyecto:**

    ```bash
    cd Limpieza-De-Datos-Melbourne
    ```

3.  **Explora los notebooks o scripts:** Busca archivos `.ipynb` o `.py` que contengan el código de limpieza y exploración de datos.

4.  **Considera crear un entorno virtual (opcional pero recomendado):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # En Linux/macOS
    venv\Scripts\activate  # En Windows
    pip install -r requirements.txt # Si tienes un archivo de requerimientos
    ```
