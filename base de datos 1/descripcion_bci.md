# Clasificación de señales de interfaz cerebro-computadora (BCI)

## Descripción general

* **Nombre:** BCI Signal Classification Dataset
* **¿Qué es?** Conjunto de registros de actividad cerebral (tipo EEG) resumidos en potencia por bandas de frecuencia (delta, theta, alfa, beta y gamma), junto con la calidad de la señal, la tarea mental realizada y el estado cognitivo del sujeto. Su propósito es entrenar y evaluar modelos que clasifiquen el estado cognitivo (enfocado, relajado, fatigado, distraído) a partir de la señal, como se hace en interfaces cerebro-computadora (BCI).
* **¿Cómo se obtuvieron los datos?** Según la ficha de Kaggle, son registros por sujeto y sesión. Generados sintéticamente con fines de investigación y educativos.No incluye datos clínicos ni de pacientes reales.
* **Fuente / URL:** https://www.kaggle.com/datasets/jayjoshi37/braincomputer-interface-signal-classification
* **Filas x columnas:** 3000 filas x 14 columnas
* **Formato:** CSV (bci\_signal\_classification\_dataset.csv, \~243 KB)
* **Valores nulos:** ninguno

## Descripción de columnas

|Columna|Tipo de dato|Descripción|Ejemplo|
|-|-|-|-|
|record\_id|Numérico (int)|Identificador único del registro (1 a 3000)|1|
|subject\_id|Numérico (int)|Identificador del sujeto (1 a 50)|39|
|session\_id|Numérico (int)|Número de sesión de registro (1 a 10)|7|
|timestamp\_ms|Numérico (int)|Instante de la medición dentro de la sesión, en milisegundos|274864|
|delta\_band\_power|Numérico (float)|Potencia de la banda delta (0.5-4 Hz)|0.680|
|theta\_band\_power|Numérico (float)|Potencia de la banda theta (4-8 Hz)|5.517|
|alpha\_band\_power|Numérico (float)|Potencia de la banda alfa (8-12 Hz)|0.800|
|beta\_band\_power|Numérico (float)|Potencia de la banda beta (12-30 Hz)|7.176|
|gamma\_band\_power|Numérico (float)|Potencia de la banda gamma (>30 Hz)|0.898|
|signal\_noise\_ratio|Numérico (float)|Relación señal-ruido de la medición (5.02 a 39.98)|23.21|
|eye\_blink\_artifact|Texto (str)|Si hay artefacto de parpadeo: Yes / No|No|
|mental\_task\_type|Texto (str)|Tarea mental: Resting, Visual Stimulus, Cognitive Load, Motor Imagery|Visual Stimulus|
|focus\_level\_score|Numérico (float)|Puntaje de nivel de concentración (0 a 100)|98.03|
|cognitive\_state|Texto (str)|Estado cognitivo (variable objetivo): Focused, Relaxed, Fatigued, Distracted|Distracted|

## Relevancia biomédica

Las señales cerebrales y las interfaces cerebro-computadora son un área central de la ingeniería biomédica (neuroingeniería, rehabilitación, monitoreo de fatiga y atención).

