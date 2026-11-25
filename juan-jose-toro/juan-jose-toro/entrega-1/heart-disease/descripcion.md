# Heart Disease – Cleveland (UCI Machine Learning Repository)

## Descripción general
- **Nombre:** Heart Disease Data Set (subconjunto Cleveland, archivo `processed.cleveland.data`)
- **¿Qué es?** Base de datos clínica de pacientes evaluados por sospecha de enfermedad coronaria. Reúne datos demográficos, síntomas, resultados de pruebas en reposo y de esfuerzo (ECG, frecuencia cardíaca, fluoroscopia, talio) y el diagnóstico angiográfico. Se usa para clasificar presencia o ausencia de enfermedad cardíaca.
- **¿Cómo se obtuvieron los datos?** Son registros clínicos de pacientes recopilados por cuatro instituciones (Hungarian Institute of Cardiology, University Hospital de Zurich, University Hospital de Basilea y V.A. Medical Center Long Beach / Cleveland Clinic Foundation, investigador principal Robert Detrano). Donante: David W. Aha (1988). Los nombres y números de seguro social fueron reemplazados por valores ficticios. La base completa tiene 76 atributos; el archivo procesado de Cleveland conserva los 14 usados en la literatura.
- **Fuente / URL de descarga:** UCI Machine Learning Repository, "Heart Disease" – https://archive.ics.uci.edu/dataset/45/heart+disease
- **Filas x columnas:** 303 filas x 14 columnas (sin fila de encabezado)
- **Formato:** archivo de texto separado por comas (`.data`, equivalente a CSV). Los nombres de columnas están en `heart-disease.names`.
- **Valores faltantes:** 6 (marcados con `?`: 4 en `ca` y 2 en `thal`).

## Descripción de columnas
| Nombre de columna | Tipo de dato | Descripción | Ejemplo de valor |
|---|---|---|---|
| age | Numérico (int) | Edad del paciente en años | 63 |
| sex | Categórico (binario) | Sexo (1 = hombre, 0 = mujer) | 1 |
| cp | Categórico (1–4) | Tipo de dolor torácico (1 = angina típica, 2 = angina atípica, 3 = dolor no anginoso, 4 = asintomático) | 1 |
| trestbps | Numérico (int) | Presión arterial en reposo al ingreso (mm Hg) | 145 |
| chol | Numérico (int) | Colesterol sérico (mg/dl) | 233 |
| fbs | Categórico (binario) | Glucosa en ayunas > 120 mg/dl (1 = verdadero, 0 = falso) | 1 |
| restecg | Categórico (0–2) | Resultado del electrocardiograma en reposo (0 = normal, 1 = anomalía de onda ST-T, 2 = probable hipertrofia ventricular izquierda) | 2 |
| thalach | Numérico (int) | Frecuencia cardíaca máxima alcanzada | 150 |
| exang | Categórico (binario) | Angina inducida por ejercicio (1 = sí, 0 = no) | 0 |
| oldpeak | Numérico (float) | Depresión del segmento ST inducida por el ejercicio respecto al reposo | 2.3 |
| slope | Categórico (1–3) | Pendiente del segmento ST en el pico de ejercicio (1 = ascendente, 2 = plana, 3 = descendente) | 3 |
| ca | Numérico (0–3) | Número de vasos principales coloreados por fluoroscopia | 0 |
| thal | Categórico (3, 6, 7) | Resultado de la prueba de talio (3 = normal, 6 = defecto fijo, 7 = defecto reversible) | 6 |
| num | Categórico (0–4) | Diagnóstico de enfermedad cardíaca por angiografía (0 = ausencia; 1–4 = presencia, en distintos grados) | 0 |
