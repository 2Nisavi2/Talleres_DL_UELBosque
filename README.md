# Solución Taller 1 Deep Learning

Desarrollado por
:alien:Daniela Ramos
:snake:Walter Garcia
:trollface:Nicolás Ávila

## __"Que son los datos de entrenamiento, validacion y prueba (train-test-validation)?"__

Dentro del desarrollo de modelos de Machine Learning, existe la tarea de particionar la data apra el proceso de diseño del modelo. La data se particiona en tres secciones:

1. Data de entrenamiento (training set): consiste en los datos que entrenaran el modelo inicialmente. Dichos datos contienen cierto comportamiento que el modelo tratará de simular. Esta data por lo general puede representar un grupo mayoritario de la totalidad de los datos que normalmente se considera que puede representar entre el 60% y el 80%, pero dicha configuración es definida por los diseñadores del modelo. Al alimentar el modelo con esta data, es posible que generen datos de sobrestimación o subestimación, los cuales son arreglados por medio de la data de validación.

2. Data de validación (Dev set o Development set): se caracteriza por una partición especifica de la totalidad de los datos que será utilizada para validar la calidad del modelo desde su entrenamiento. Los datos de validación permiten configurar el modelo entrenado para lograr un equilibrio entre el error y el bias sin presentar subestimaciones o sobrestimaciones.

3. Data de prueba: 