# Proyecto-Machine-Learning
Datathon

## Introduccion.

👋🏻 Mi nombre es Eugenia Ball. Al momento de hacer este proyecto me encontré cursando la etapa de Labs para la carrera de Data Science de SoyHenry .

​ Dentro de la sociedad globalizada e industrializada, es sabido que los precios de los inmuebles han presentado un cambio constante, por lo que quienes desean
 invertir o vender una propiedad se enfrentan al fenómeno especulativo existente en la valorización de estos. 
 Esto, debido a la constante tendencia de las ciudades a crecer demográfica y comercialmente, llegando a un punto en donde no se tiene certeza de la valorización real 
 dentro del sector en donde se desea invertir. ​ 🏫🏢
 Pese a que el precio depende, en cierta medida, de las tendencias que esté teniendo el mercado inmobiliario en un tiempo determinado, poder estimar adecuadamente el valor
 de una propiedad es una referencia clave para entender si es una buena oportunidad, ya sea de compra o de venta. 

 ## Descripcion del problema.
 
Este proyecto se basa en el desarrollo de un modelo de aprendizaje automático para estudiar ciertas características del mercado inmobiliario en Estados Unidos.
El modelo debe evaluar los precios de diferentes inmuebles y predecir si el precio 1 si es 'low' o 0 si es 'medium' o 'high'. 
La clasificacion entre estas categorias se debe hacer tomando en cuenta los precios de las propiedades del archivo train.parquet, sus caracteristicas y el indice de correlacion
entre las variables.

## Eda.💻

En el proceso de EDA se realizaron varias transformaciones a los datos contenidos en el documento "train.parquet". Se identificaron las columnas 
con valores nulos y esas columnas fueron reemplazadas para no perder los datos. Se borraron duplicados en descripcion

Luego las variables categoricas se pasaron a dummies para poder usar esas columnas para entrenar el modelo.

Antes de poner a funcionar el modelo ,se uso pipeline. Pipeline funciona como una canalización para organizar el flujo de 
datos hacia un modelo  (o un conjunto de múltiples modelos) y la salida de este . Incluye entrada de datos sin procesar,
 características, salidas, el modelo usado y parámetros del modelo, y salidas de predicción.



 ## Archivos provistos

 limpieza.csv
