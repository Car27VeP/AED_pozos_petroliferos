# Descricpión del Proyecto. 

**OilyGiant es una empresa dedicada a la extracción de petroleo.**

La tarea es encontrar los mejores lugares donde abrir 200 pozos nuevos de petróleo.

Se relizarán los siguientes pasos para completar esta tarea.

- Leer los archivos con los parámetros recogidos de pozos petrolíferos en la región seleccionada: calidad de crudo y volumen de reservas.
- Crear un modelo para predecir el volumen de reservas en pozos nuevos.
- Elegir los pozos petrolíferos que tienen los valores estimados más altos.
- Elegir la región con el beneficio total más alto para los pozos petrolíferos seleccionados.

Se tienen datos sobre muestras de crudo de tres regiones. Ya se conocen los parámetros de cada pozo petrolero de la región. Se creará un modelo que ayude a elegir la región con el mayor margen de beneficio. Analiza los beneficios y riesgos potenciales utilizando la técnica *bootstrapping*.

**Condiciones**:

- Solo se debe usar la regresión lineal para el entrenamiento del modelo.
- Al explorar la región, se lleva a cabo un estudio de 500 puntos con la selección de los mejores 200 puntos para el cálculo del beneficio.
- El presupuesto para el desarrollo de 200 pozos petroleros es de 100 millones de dólares.
- Un barril de materias primas genera 4.5 USD de ingresos. El ingreso de una unidad de producto es de 4500 dólares (el volumen de reservas está expresado en miles de barriles).
- Después de la evaluación de riesgo, mantén solo las regiones con riesgo de pérdidas inferior al 2.5%. De las que se ajustan a los criterios, se debe seleccionar la región con el beneficio promedio más alto.

**Descripción de datos:**

Los datos de exploración geológica de las tres regiones se almacenan en archivos:

- `geo_data_0.csv`. Descarga el conjunto de datos
- `geo_data_1.csv`. Descarga el conjunto de datos
- `geo_data_2.csv`. Descarga el conjunto de datos
- `id` — identificador único de pozo de petróleo
- `f0`, `f1`, `f2` — tres características de los puntos (su significado específico no es importante, pero las características en sí son significativas)
- `product` — volumen de reservas en el pozo de petróleo (miles de barriles).