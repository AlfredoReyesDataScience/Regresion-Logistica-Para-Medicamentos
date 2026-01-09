## Dataset

Drugs.csv

Variables: Edad, sexo, presion arterial,etc

## Problema

Imagina que eres un investigador médico que recopila datos para un estudio. Has recopilado datos sobre un conjunto de pacientes, todos ellos con la misma enfermedad. Durante su tratamiento, cada paciente ha respondido a uno de los 5 medicamentos, el fármaco A, el fármaco B, el fármaco C (de proveedor nacional), el fármaco X y el Y (de proveedor extranjero). 

Parte de tu trabajo consiste en construir un modelo para averiguar qué medicamento podría ser apropiado para un futuro paciente con la misma enfermedad. Los conjuntos de características de este conjunto de datos son la edad, el sexo, la presión arterial y el colesterol de los pacientes, y el objetivo es estudiar el fármaco al que respondió cada paciente. 


## Técnicas utilizadas

Regresión logísitica en sus distintas variantes (SAG, Liblinear, etc)

Generación de reportes para cada modelo de manera individual

Comparación entre distintos modelos de regresión logística

Conversión de variables cualitativas a cuantitativas para poder generar modelos más eficientes


 ## Resultados principales

Se obtuvo que el mejor modelo de regresión logísitica para éste caso fue el Newton-CG con un Score de Precisión del 94%
               precision    recall  f1-score   support

           0       0.75      1.00      0.86         6
           1       1.00      0.75      0.86         4
           2       1.00      0.50      0.67         4
           3       1.00      1.00      1.00        13
           4       0.96      1.00      0.98        23

    accuracy                           0.94        50
   macro avg       0.94      0.85      0.87        50
weighted avg       0.95      0.94      0.93        50

<img width="577" height="467" alt="image" src="https://github.com/user-attachments/assets/a5a4ea88-a92c-4fe9-b48d-de777b296966" />


## Qué aprendí

Modelos de regresión logísitica

Conversión de variables cualitativas para eficientar modelado

