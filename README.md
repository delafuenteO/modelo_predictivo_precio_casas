# Predicción del valor de casas usadas en Chile
Introducción
En este notebook se utiliza la técnica de regresión lineal para estimar el precio en UF de las casas usadas en la Región Metropolitana de Chile, basándose en un dataset de Kaggle que contiene información sobre el tipo, la superficie, el número de habitaciones, el número de baños, el año de construcción y la ubicación de las propiedades.

Herramientas y lenguajes
Para crear este notebook se usaron las siguientes herramientas y lenguajes:

Python 3.9
pandas
matplotlib
scikit-learn
seaborn
Detalles del proyecto

## El proyecto se divide en las siguientes secciones: ##

- Importación de librerías y carga de datos: en esta sección se importan las librerías necesarias y se carga el dataset de Kaggle usando pandas. Se muestra el tamaño, las columnas y los primeros registros del dataframe.

- Limpieza y transformación de datos: en esta sección se realizan algunas operaciones de limpieza y transformación de los datos, como eliminar los valores nulos, cambiar el tipo de algunas columnas, crear nuevas variables y eliminar las variables innecesarias.

- Análisis exploratorio de datos: en esta sección se realizan algunos análisis estadísticos y gráficos sobre las variables del dataset, como el cálculo de medidas de tendencia central y dispersión, la distribución de frecuencias, el análisis de correlación y la visualización de mapas, histogramas y diagramas de caja.

- Entrenamiento y evaluación del modelo de regresión lineal: en esta sección se divide el dataset en conjuntos de entrenamiento y prueba, se crea y entrena el modelo de regresión lineal usando scikit-learn, se evalúa el rendimiento del modelo usando el coeficiente de determinación (R2) y el error cuadrático medio (MSE), y se visualizan los residuos y la línea de regresión.

- Predicción con el modelo: en esta sección se hace una predicción con el modelo usando un ejemplo de una casa usada con ciertas características, y se muestra el resultado en UF.

## Instalación y ejecución ##
Para instalar y ejecutar el notebook, se requieren los siguientes pasos:

Clonar o descargar el repositorio de GitHub que contiene el notebook y el dataset.
Instalar las librerías necesarias usando el comando pip install -r requirements.txt en la terminal.
Abrir el notebook usando Jupyter Notebook o cualquier otro editor compatible con Python.
Ejecutar las celdas del notebook siguiendo el orden indicado.

## Colaboración ##
Si quieres colaborar con este proyecto, puedes hacer lo siguiente:

Hacer un fork del repositorio de GitHub y crear una rama con tus cambios.
Hacer un pull request al repositorio original con una descripción de tus aportes.
Dejar un comentario o una sugerencia en el notebook de Kaggle.
