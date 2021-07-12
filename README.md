# Feed Forward Neural Networks


En el presente repositorio muestro un conjunto de códigos en donde se implementa 

el entrenamiento de redes neuronales "Feed Forward" para la clasificación de objetos.

Este tipo de redes neuronales son eficientes en la detección de patrones en la información. 


En el código 'c0_RNA_a_mano_function_XOR.ipynb' he construido el proceso de entrenamiento 

desde ceros, esto con el objetivo de entender como funcionan las "cajas negras" de paquetes 

como TensorFlow.


En el código 'c5_RNA_profunda_sin_labels_codificadas_CIFAR10_data.ipynb' muestro que 

que las redes "Feed Forward" pueden ser ineficientes al clasificar imágenes a color, en este caso 

la solución es usar "Redes Convolucionales".


Muestro dos versiones de código, una en donde se entrena la red usando la función de costo

`loss = 'categorical_crossentropy'` la cual requiere una codificación de las etiquetas; 

en la otra versión entrenamos la red usando la función de costo 

`loss = 'sparse_categorical_crossentropy'` la cual NO requiere una codificación de las etiquetas.
