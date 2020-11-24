# RandomForestClassifier

<div align="center">

**Instituto Tecnológico de Tijuana**

Departamento de Ciencias y Computación

Ingeniería en Sistemas Computacionales
 
 [![](https://upload.wikimedia.org/wikipedia/commons/2/2e/ITT.jpg)](https://upload.wikimedia.org/wikipedia/commons/2/2e/ITT.jpg)

**Title:**
Random Forest Classifier

**Subject:**
BDD-1704 SC9A Datos Masivos

**Unit:**
 II

**Professor:**
JOSE CHRISTIAN ROMERO HERNANDEZ

**Team 3**

ARREDONDO GOMEZ RAMON ALEJANDRO     15210326

AULIS SANCHEZ VICTOR JAIR           17212836

BOJORQUEZ VARGAS CARLOS FRANCISCO   16211977

CABRERA LUGO ALBERTO                17210533 

**Group:**
SC9A

**Date:**
Tijuana, Baja California, November 23, 2020. 
</div>


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


### DIFERENCIAS ENTRE DECISION TREES Y RANDOM FOREST
Si bien el bosque aleatorio es una colección de árboles de decisión, existen algunas diferencias.

Si ingresa un conjunto de datos de entrenamiento con características y etiquetas en un árbol de decisiones, se formularán algunas reglas, que se utilizarán para hacer las predicciones.

Por ejemplo, para predecir si una persona hará clic en un anuncio en línea, puede recopilar los anuncios en los que la persona hizo clic en el pasado y algunas características que describen su decisión. Si coloca las características y etiquetas en un árbol de decisiones, se generarán algunas reglas que ayudarán a predecir si se hará clic en el anuncio o no. En comparación, el algoritmo de bosque aleatorio selecciona al azar observaciones y características para construir varios árboles de decisión y luego promedia los resultados.

Otra diferencia es que los árboles de decisión "profundos" pueden sufrir un ajuste excesivo. La mayoría de las veces, el bosque aleatorio evita esto creando subconjuntos aleatorios de las características y construyendo árboles más pequeños usando esos subconjuntos. Posteriormente, combina los subárboles. Es importante tener en cuenta que esto no funciona todas las veces y también hace que el cálculo sea más lento, dependiendo de cuántos árboles construya el bosque aleatorio.

<div align="center">
  
**Decision Tree**

![Decision Tree](https://miro.medium.com/max/625/1*LMoJmXCsQlciGTEyoSN39g.jpeg "Decision Tree")

**Random Forest**

![Random Forest](https://miro.medium.com/max/625/1*VHDtVaDPNepRglIAv72BFg.jpeg "Random Forest")

</div>

### POR QUE USAR EL ALGORITMO RANDOM FOREST 

Para responder a esta pregunta, sugeriremos algunas de sus ventajas y características importantes que aclararán su mente por qué utilizar el algoritmo de RF en el aprendizaje automático.

•	El algoritmo de bosque aleatorio se puede utilizar tanto para clasificaciones como para tareas de regresión.
•	Proporciona una mayor precisión a través de la validación cruzada.
•	El clasificador de bosque aleatorio manejará los valores faltantes y mantendrá la precisión de una gran proporción de datos.
•	Si hay más árboles, no permitirá el ajuste excesivo de árboles en el modelo, no los aceptara.
•	Tiene el poder de manejar un gran conjunto de datos con mayor diversidad en sus dimensiones.

### ¿CUANDO USAR EL ANALISIS DE BOSQUES ALEATORIOS?

Hay varias aplicaciones donde se puede aplicar un análisis de RF. Discutiremos algunos de los sectores donde se puede aplicar el bosque aleatorio. También veremos más de cerca cuando el análisis de bosque aleatorio entre en juego.

•	Sector bancario: El sector bancario se compone de la mayoría de los usuarios. Hay muchos clientes leales y también clientes fraudulentos. Para determinar si el cliente es leal o fraudulento, entra el análisis de bosque aleatorio. Con la ayuda de un algoritmo de bosque aleatorio en el aprendizaje automático, podemos determinar fácilmente si el cliente es fraude o leal. Un sistema utiliza un conjunto de algoritmos aleatorios que identifica las transacciones fraudulentas mediante una serie de patrones.

•	Medicamentos: Los medicamentos necesitan una combinación compleja de productos químicos específicos. Así, para identificar la gran combinación en las medicinas, se puede utilizar Random Forest. Con la ayuda del algoritmo de aprendizaje automático, se ha vuelto más fácil detectar y predecir la sensibilidad a los medicamentos de un medicamento. Además, ayuda a identificar la enfermedad del paciente mediante el análisis de la historia clínica del paciente.

•	Mercado de valores: El aprendizaje automático también juega un papel en el análisis del mercado de valores. Cuando se desea conocer el comportamiento del mercado de valores, con la ayuda del algoritmo de bosque aleatorio, se puede analizar el comportamiento del mercado de valores. Además, puede mostrar la pérdida o ganancia esperada que se puede producir al comprar una acción en particular.

•	Comercio Electrónico (E-Commerce): Cuando le resulte difícil recomendar o sugerir qué tipo de productos debe ver su cliente. Aquí es donde puede utilizar un algoritmo de bosque aleatorio. Usando un sistema de aprendizaje automático, puede sugerir los productos que serán más probables para un cliente. Usando un patrón determinado y siguiendo el interés del producto de un cliente, puede sugerir productos similares a sus clientes.



```scala
import org.apache.spark.ml.Pipeline
import org.apache.spark.ml.classification.{RandomForestClassificationModel, RandomForestClassifier}
import org.apache.spark.ml.evaluation.MulticlassClassificationEvaluator
import org.apache.spark.ml.feature.{IndexToString, StringIndexer, VectorIndexer}

// Load and parse the data file, converting it to a DataFrame.
val data = spark.read.format("libsvm").load("C:\\Users\\beto_\\Desktop\\Datos//Masivos//clase\\Spark\\data\\mllib\\sample_libsvm_data.txt")
//val data = spark.read.format("libsvm").load("C:\\spark-2.4.7-bin-hadoop2.7\\data\\mllib\\sample_libsvm_data.txt")

// Index labels, adding metadata to the label column.
// Fit on whole dataset to include all labels in index.
val labelIndexer = new StringIndexer()
  labelIndexer.setInputCol("label")
  labelIndexer.setOutputCol("indexedLabel")
  labelIndexer.fit(data)

// Automatically identify categorical features, and index them.
// Set maxCategories so features with > 4 distinct values are treated as continuous.
val featureIndexer = new VectorIndexer()
  featureIndexer.setInputCol("features")
  featureIndexer.setOutputCol("indexedFeatures")
  featureIndexer.setMaxCategories(4)
  featureIndexer.fit(data)

// Split the data into training and test sets (30% held out for testing).
val Array(trainingData, testData) = data.randomSplit(Array(0.7, 0.3))

// Train a RandomForest model.
val rf = new RandomForestClassifier()
  rf.setLabelCol("indexedLabel")
  rf.setFeaturesCol("indexedFeatures")
  rf.setNumTrees(10)

// Convert indexed labels back to original labels.
val labelConverter = new IndexToString()
  labelConverter.setInputCol("prediction")
  labelConverter.setOutputCol("predictedLabel")
  labelConverter.setLabels(labelIndexer.labelsArray(0)) //Aqui marca error <console>:32: error: value labelsArray is not a member of org.apache.spark.ml.feature.StringIndexer

// Chain indexers and forest in a Pipeline.
val pipeline = new Pipeline()
  pipeline.setStages(Array(labelIndexer, featureIndexer, rf, labelConverter))

// Train model. This also runs the indexers.
val model = pipeline.fit(trainingData)

// Make predictions.
val predictions = model.transform(testData)

// Select example rows to display.
predictions.select("predictedLabel", "label", "features").show(5)

// Select (prediction, true label) and compute test error.
val evaluator = new MulticlassClassificationEvaluator()
  evaluator.setLabelCol("indexedLabel")
  evaluator.setPredictionCol("prediction")
  evaluator.setMetricName("accuracy")
val accuracy = evaluator.evaluate(predictions)
println(s"Test Error = ${(1.0 - accuracy)}")

val rfModel = model.stages(2).asInstanceOf[RandomForestClassificationModel]

println(s"Learned classification forest model:\n ${rfModel.toDebugString}")
```
