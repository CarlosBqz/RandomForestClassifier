# RandomForestClassifier
Team 3

ARREDONDO GOMEZ RAMON ALEJANDRO

AULIS SANCHEZ VICTOR JAIR

BOJORQUEZ VARGAS CARLOS FRANCISCO

CABRERA LUGO ALBERTO



### ¿Qué es y cómo funciona random forest classifier?
Random Forest es un algoritmo de aprendizaje supervisado. El "bosque" que se genera es un conjunto de árboles de decisión, usualmente entrenados usando el método "bagging". La idea general de este método es que la combinación de diferentes modelos de aprendizaje incremente el resultado generado.

**En pocas palabras**: Random Forest construye múltiples árboles de decisión y los fusiona para obtener una predicción más precisa y estable.

Una gran ventaja del Random Forest Classifier es que puede utilizarse tanto para problemas de clasificación como de regresión, que constituyen la mayoría de los sistemas actuales de aprendizaje por máquina.

![Ejemplo de Random Forest Classifier usando dos árboles de decisión](https://builtin.com/sites/default/files/styles/ckeditor_optimize/public/inline-images/two-tree-random-forest.png "Ejemplo de Random Forest Classifier usando dos árboles de decisión")

Random forest agrega aleatoriedad adicional al modelo, mientras genera los árboles. En lugar de buscar la característica más importante al dividir un nodo, busca la mejor característica entre un subconjunto aleatorio de características. Esto da como resultado una amplia diversidad que generalmente resulta en un mejor modelo.

Por lo tanto, el algoritmo solo tiene en cuenta un subconjunto aleatorio de las características para dividir un nodo. Incluso puede hacer que los árboles sean más aleatorios si utiliza umbrales aleatorios para cada característica en lugar de buscar los mejores umbrales posibles (como lo hace un árbol de decisiones normal).

### Analogía usando un caso real
Andrew quiere decidir a dónde ir durante las vacaciones, por lo que pide sugerencias a las personas que lo conocen mejor. El primer amigo que busca le pregunta sobre los gustos y disgustos de sus viajes pasados. Según las respuestas, le dará a Andrew algunos consejos.

Este es un enfoque típico de un algoritmo de árbol de decisión. El amigo de Andrew creó reglas para guiar su decisión sobre lo que debería recomendar, utilizando las respuestas de Andrew.

Luego, Andrew comienza a pedirle a más y más amigos que lo aconsejen y nuevamente le hacen diferentes preguntas que pueden usar para derivar algunas recomendaciones. Finalmente, Andrew elige los lugares que más le recomiendan, que es el enfoque típico del Random Forest Classifier.

![Ejemplo](https://mlux9brz2apw.i.optimole.com/y1pDtVQ-NL9wTwiU/w:1024/h:581/q:auto/https://kgptalkie.com/wp-content/uploads/2020/08/image-122.png "Ejemplo")
