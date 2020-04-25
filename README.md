# COVID-19 🦠

Este es un repositorio de estudio y procesamiento de los datos del COVID-19 para el entrenamiento de modelos de Machine Learning que puedan ayuar a predecir datos como cantidad de contagiados o de muertos futuros, correlacion entre paises, etc..

### 🇨🇴 Colombia 
El estudio comienza filtrandose para colombia y haciendo una comparacion de varios metodos de regresion para el entrenamiento de un modelo predictor. Se parte de la base de querer predecir la cantidad de contagiados del dia siguiente. Puede encontrar un cuaderno de Python con la comparacion de los metodos [Aqui](https://github.com/dacardonave/COVID-19/blob/master/Analisis_Comparativo_Metodos_de_Regresion_Covid19.ipynb).

### 🇨🇳 China 
En otro Notebook de python que puede encontrar[Aqui](https://github.com/dacardonave/COVID-19/blob/master/An%C3%A1lisis_China_Regresi%C3%B3n_Lineal_Simple_Covid19.ipynb), podra ver el analisis y diseño de un modelo predictivo para el comportamiento de los contagiados en China con la ayuda de un modelo lineal de [Scikit-Learn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html). El dataset usado en este notebook lo puede encontrar adjunto [aqui](https://github.com/dacardonave/COVID-19/blob/master/China/china.csv) y contiene datos de muertos, contagiados y recuperados desde el 22 de enero de 2020 hasta el 18 de abril de 2020. Este dataset se obtiene de filtrar previamente un [dataset mundial de COVID-19](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset#time_series_covid_19_confirmed.csv).
