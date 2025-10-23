# SVM-y-Multiple-Testing


**Nombre:** Juan Rodrigo Guerrero De la Garza  
**Matrícula:** 611471  

**Objetivo:** Ser capaz de generar un modelo de SVM para resolver un problema de clasificación y realizar inferencias ajustando por múltiples pruebas.


---
El dataset “Khan.csv” proviene de un estudio de microarreglos de ADN utilizado para analizar la expresión génica en diferentes tipos de tumores humanos.
Cada observación corresponde a una muestra de tejido, y cada variable —excepto la de clase— representa la expresión de un gen específico medida experimentalmente.

En concreto, el conjunto contiene:
- 83 observaciones (muestras de pacientes).
- 2 308 variables de genes más una columna de clase (y).
- La columna y toma valores 1, 2, 3 y 4, que identifican los cuatro tipos de tumores:
  - Clase 1: Tumor del sistema linfático.
  - Clase 2: Tumor de colon.
  - Clase 3: Tumor de pulmón.
  - Clase 4: Tumor del sistema nervioso central.

El objetivo del análisis es identificar qué genes presentan diferencias significativas en su nivel de expresión entre los distintos tipos de tumores, y posteriormente, entrenar clasificadores SVM que puedan predecir el tipo de tumor en función del perfil de expresión genética de cada muestra.

En otras palabras, es un problema de clasificación multiclase con variables genómicas de alta dimensionalidad (miles de genes, pocas muestras), ideal para aplicar pruebas de hipótesis, reducción de características y modelos de aprendizaje supervisado como SVM.

---

<a href="././A3.1%20611471.ipynb" download>Reporte en formato ipynb</a>  

[Reporte en formato html](./A3.1%20611471.html) 

<a href="A3.1%20khan.csv" download>Base de datos</a>  
