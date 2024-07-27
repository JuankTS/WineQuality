<h1 align='center'>Wine Quality Analysis</h1>

<p align="center">
  <img src='https://www.cronista.com/files/image/298/298236/5ffe0d2df288b.jpg'/>
</p>

En este proyecto, analizamos los datos de un dataset de [Kaggle](https://www.kaggle.com), que contiene una lista de distintos vinos junto a sus características, las cuales definen su calidad. El objetivo es analizar los datos y, con base en ellos, identificar las variables más influyentes en la calidad del vino. Luego, entrenaremos un modelo de machine learning que nos ayude a predecir dicha calidad.

<h2>
Datos y su procesamiento
<img src="https://media.giphy.com/media/DDGQgJLkOlSKe08e74/giphy.gif"  width="70" height="70">
</h2>

Para este proyecto, utilizamos un [dataset](https://www.kaggle.com/datasets/joebeachcapital/wine-quality) que es una muestra de distintos vinos, junto con sus características como el pH, el porcentaje de alcohol, azúcares residuales, entre otros. Estas características sirven para definir la calidad del vino, nuestra variable objetivo (**quality**), que es un puntaje que va de 1 a 10, basado en las características mencionadas anteriormente. En este dataset no hay valores nulos, por lo que procedemos a analizar su comportamiento con la variable objetivo mediante gráficos y correlación, para así seleccionar las variables con mayor relación con la calidad.

<h2>
Modelo
<img src="https://media.giphy.com/media/RfMwwcLajPvRUv75wD/giphy.gif"  width="70" height="70">
</h2>
</h2>

Dado que nuestras variables objetivo no pueden separarse linealmente, no utilizamos regresión logística en este ejercicio. En su lugar, optamos por un modelo de Random Forest, el cual evaluamos usando la métrica de **Accuracy**. Además, empleamos el análisis de **Feature Importance** del modelo para identificar cuáles son las variables que el algoritmo considera más importantes, y así concluir con el análisis.

Puedes ver el análisis completo [aquí](https://github.com/JuankTS/WineQuality/blob/main/Analysis/Wines.ipynb).

<div align="center">
  <a href='https://www.linkedin.com/in/juan-camilo-torres-salas-907749265/'><img src="https://skillicons.dev/icons?i=linkedin"/></a>
  <a href="mailto:torressalasjc@gmail.com"><img src="https://skillicons.dev/icons?i=gmail&theme=light" alt="Gmail"/></a>
</div>