# Machine Learning en investigación del mercado automotor
## Proyecto realizado a modo de práctica en el marco del módulo de Machine Learning del Bootcamp Data Science de Henry

A lo largo del módulo se estudiaron los conceptos principales de ML y sus aplicaciones, así como la implementación y evaluación de diferentes modelos. Además se abordaron temas como series de tiempo, modelos de ensambles, procesamiento del lenguaje natural y redes neuronales.

En el siguiente trabajo se busca abordar un caso práctico mediante diferentes modelos de predicción para alcanzar el resultado más óptimo posible.
El mismo consta de tres fases: `Análisis exploratorio de datos`, `Preparación de datos` y, `Modelamiento y evaluación`.
​
## Descripción del caso de estudio.
​​
El mercado automotor esta muy ligado a la cultura de cada país, según los gustos de cada uno, el mercado norteamericano, por ejemplo, valora mucho los motores y vehículos muy grandes, el mercado europeo prefiere el bajo consumo, el mercado latinoamericano, los precios finales bajos y asi varía según región, país, nivel socioeconómico y cultura. Un mismo vehículo puede tener un valor muy distinto de un pais al otro, y no solo por los impuestos o costos de producción, sino por cómo cotiza el modelo en el mercado.

### **Planteamiento de la problemática**
​
Hemos sido contratados en el equipo de ciencias de datos en una consultora de renombre. Nos han asignado a un proyecto de estudio de mercado de una importante automotriz china. Nuestro cliente desea ingresar a nuestro mercado de automóviles, por lo que nos han encomendado analizar las características de los vehículos presentes en el mercado actual. Dado que tienen en su catálogo una amplia colección de modelos de todo tipo, cuyo catálogo está estratificado en gamas según el gusto de cada región, desean saber qué características presentan los vehículos de gama alta y los de gama baja en nuestro mercado, para poder abarcar todo los públicos objetivos ajustándose a toda la demanda y, en base a estos datos, poder cotizar correctamente los vehículos que ofrecerá. 

Para ello, nuestro departamento de datos ha recopilado precios y características de varios de los modelos de vehículos disponibles en nuestro mercado, junto con sus precios de venta al público. Y han armado el siguiente diccionario de datos:


![DiccionarioDatos](https://github.com/jdeiloff/Proyecto-Integrador-M6/raw/main/dic_pi2.jpg)


Nuestro Data Lead nos ha recomendado que analicemos detalladamente los datos, los preprocesemos debidamente y que diseñemos dos modelos predictivos, uno para el precio y otro para distinguir vehículos de gama alta y de gama baja, utilizando la mediana de los precios como punto de corte. Desean obtener los archivos con las predicciones en formato de texto plano.

Además del análisis detallado de la exploración de los datos, estas son las dos predicciones posibles que les interesaría analizar:
​
1. **Implementar un modelo de clasificación** con aprendizaje supervisado que permita clasificar el precio de los vehículos en baratos y caros usando la mediana de los precios como punto de corte, utilizando los datos que se han puesto a su disposición.

2. **Implementar un modelo de regresión** con aprendizaje supervisado que permita predecir el precio final de los vehículos, utilizando los datos que se han puesto a su disposición.

## Abordaje del trabajo

#### *Analisis exploratorio de datos (EDA)* 
Se realizó un analisis profundo de los datos para identificar tendencias, patrones y relaciones entre las diferentes variables.

#### *Procesamiento de datos*
En este punto se llevó a cabo la limpieza, transformación y preparación de los datos para el proceso de modelado.

#### *Selección y entrenamiento de modelos* 
Se utilizó un modelo de regresión Lineal Múltiple para obtener predicciones de precios de vehículos y para la clasificación entre gama alta y baja se diseñaron y entrenaron 3 tipos de modelos: regresión logística, KNN y árbol de decisión

#### *Evaluación de modelos* 
Se compararon diferentes métricas para analizar la performance de cada modelo y obtener conclusiones de los resultados.



## Resultado
Se lograron muy buenos resultados en cuanto al diseño y performance de los modelos desarrollados, tanto para la predicción de precios como para la clasificación de los vehículos por su gama. 
​
