# Pima Indians Diabetes Database

## Descripción general
- **Nombre:** Pima Indians Diabetes Database (archivo `pima-indians-diabetes.csv`)
- **¿Qué es?** Base de datos médica con mediciones diagnósticas de mujeres de al menos 21 años de ascendencia indígena Pima. Su propósito es predecir si una paciente tiene diabetes (variable `Outcome`) a partir de variables como glucosa, presión arterial, IMC e insulina.
- **¿Cómo se obtuvieron los datos?** Son registros clínicos recopilados por el National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) de EE. UU. a partir de pacientes seleccionadas de una población más grande. Está disponible en Kaggle y en el repositorio UCI.
- **Fuente / URL de descarga:** Kaggle – https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database (también disponible en UCI Machine Learning Repository). *Verificar que este sea el enlace desde el que se descargó el archivo.*
- **Filas x columnas:** 768 filas x 9 columnas (el archivo no trae fila de encabezado; los nombres se tomaron de la documentación de la fuente).
- **Formato:** CSV
- **Valores faltantes:** no hay celdas vacías, pero en varias columnas el valor 0 es biológicamente imposible y representa un dato faltante (por ejemplo `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`). Los datos se dejaron tal como se descargaron.

## Descripción de columnas
El orden corresponde a las columnas del archivo, de izquierda a derecha.

| Nombre de columna | Tipo de dato | Descripción | Ejemplo de valor |
|---|---|---|---|
| Pregnancies | Numérico (int) | Número de embarazos | 6 |
| Glucose | Numérico (int) | Concentración de glucosa en plasma a las 2 horas de una prueba oral de tolerancia a la glucosa | 148 |
| BloodPressure | Numérico (int) | Presión arterial diastólica (mm Hg) | 72 |
| SkinThickness | Numérico (int) | Grosor del pliegue cutáneo del tríceps (mm) | 35 |
| Insulin | Numérico (int) | Insulina sérica a las 2 horas (mu U/ml) | 0 |
| BMI | Numérico (float) | Índice de masa corporal (peso en kg / estatura en m²) | 33.6 |
| DiabetesPedigreeFunction | Numérico (float) | Función de pedigrí de diabetes: puntaje de predisposición según antecedentes familiares | 0.627 |
| Age | Numérico (int) | Edad en años | 50 |
| Outcome | Categórico (binario) | Diagnóstico (1 = diabetes, 0 = sin diabetes) | 1 |
