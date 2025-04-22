# PCA-LFW
Una práctica haciendo uso de PCA en el conjunto de datos Labelled Faces in the Wild.

Se considera el conjunto de datos Labelled Faces in the Wild (LFW) que consiste en fotografías de rostros recolectados de internet y contenido en *sklearn*. Algunos rostros identificados, tienen varias fotos incluídas en el dataset. Vamos a considerar solo aquellas personas que tienen al menos 70 fotografías de su rostro, también, vamos a considerar el tamaño original de la imagen $(125 \times 94)$.

Se realiza lo siguiente:
* Obtención las eigenfaces del conjunto de entrenamiento. Visualización de los scores de los primeros dos componentes principales identificando patrones.
* Proyección de los datos de prueba en los componentes principales. Se verifica si se *ubican* en su *individuo* correspondiente al graficarlos en los primeros dos componentes principales.
* Se utiliza el método del vecino más cercano para identificar a un *sujeto* de prueba en las imágenes de entrenamiento. Se considera sa la distancia euclideana en el espacio de los $p$ componentes principales, además se decide qué valor de $p$ usar.
* Se considera una(s) imágen(es) que no están en la base de datos y se realiza la prueba. 


## Resultados importantes.
