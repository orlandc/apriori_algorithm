# Algoritmo Apriori 

## Association Rules Mining - Market Basket Analysis

Desarrollo de un análisis de asociación en Python usando el algoritmo a priori para derivar reglas de la forma {A, B} -> {C}, usando los datos del problema Instacart Market [link](https://www.kaggle.com/datatheque/association-rules-mining-market-basket-analysis/notebook) en Kaggle, teniendo en cuenta las siguientes caracteristicas:

* minimum Support: 1%
*     confidence: 70%


### Notas de Desarrollo

El ejercicio establece un minimum Support: 1%, pero con esta condición el filtro encuentra 2 registros, por lo tanto se prueba con:

minimum Support: 0.5%

minimum Support: 0.04%

Nota: Para el cálculo de minimum Support Count se usa la formula explicada en la pagina 5 del [pdf](https://www3.cs.stonybrook.edu/~cse634/lecture_notes/07apriori.pdf)

### Conclusiones

* El minimum Support propuesto en el problema inicial de 1%, no es posible alcanzarlos para las relaciones {A, B} -> {C} ya que el conteo es muy alto debido a la cantidad de registros.


* El proceso de cálculo de C2 es el mas complejo debido al alto volumen de datos, por lo cual es necesario revisar otras técnicas de procesado de información.