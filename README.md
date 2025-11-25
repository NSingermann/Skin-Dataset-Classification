# Skin-Dataset-Classification
Trabajo Práctico para la materia de Redes Neuronales

# Brief

Inicialmente se ejecutó la notebook **`0_EDA.ipynb`**, la cual resultó útil para familiarizarse con el dataset.

Luego se trabajó extensamente sobre la notebook **`1_Modelo Simple.ipynb`**. Esta fue modificada considerablemente, principalmente agregando numerosos experimentos para visualizarlos de forma clara en **TensorBoard**.  
Todos los experimentos se encuentran en la carpeta **`runs/`** y están documentados con su correspondiente título. Para visualizar todas las runs en **TensorBoard** se utiliza el comando *tensorboard --logdir=runs/*

Esta primer instancia resultó clave para responder la mayoria de las preguntas; otras fueron investigadas en internet.

Posteriormente se ejecutó la notebook **`2_Modelo Simple con búsqueda de HP.ipynb`**, la cual —me di cuenta tarde— debí haberla corrido en mi PC (puesto a los recursos que tiene disponible), no en la laptop.  
La ejecución tomó aproximadamente **12 horas**, durante las cuales se evaluaron **88 modelos**, analizando cuál obtuvo el mejor desempeño.

Finalmente se ejecutó la notebook **`3_CNN con búsqueda de HP.ipynb`** en la PC, entrenando **75 modelos** en aproximadamente **5 horas**.

Todas las preguntas teóricas y el análisis de los resultados fueron contrastados en el informe, **MLFlow** resultó ser de gran utilidad principalmente para las búsquedad de hiperparámetros. 

**Es importante destacar que el proyecto debió ser comprimido debido a su gran tamaño.**

---
### PD
Existen dos archivos comprimidos:

- **Skin Classification MLP**  
  Ejecutado completamente en la laptop (no contiene las *runs* del CNN).

- **Skin Classification CNN**  
  Contiene las *runs* del MLP realizadas con la laptop (excepto la búsqueda de HP)  y las *runs* de búsqueda de HP correspondientes a la CNN.