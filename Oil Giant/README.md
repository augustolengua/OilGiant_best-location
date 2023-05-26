## Data:


- *id* — identificador único de pozo de petróleo
- *f0*, *f1*, *f2* — tres características de los puntos (su significado específico no es importante, pero las características en sí son significativas)
- *product* — volumen de reservas en el pozo de petróleo (miles de barriles).

## Goal:

Se tiene datos sobre muestras de crudo de tres regiones. Ya se conocen los parámetros de cada pozo petrolero de la región. Se tiene que crear un modelo que ayude a elegir la región con el mayor margen de beneficio analizando los beneficios y riesgos potenciales utilizando la técnica bootstrapping.

## Libraries used:

pandas

numpy

sklearn.preprocessing

sklearn.model_selection

sklearn.linear_model

sklearn.metrics