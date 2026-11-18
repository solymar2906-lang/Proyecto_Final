**BASE DE DATOS DE SALUD Y SANGRE.**

**Descripción general.**

- Nombre de la base de datos: Diabetes Classification.csv (prueba de salud por conjunto de datos)

- Formato del archivo: CSV

- Fuente / URL de descarga: Fue sacada de Kaggle https://www.kaggle.com/datasets/simaanjali/diabetes-classification-dataset

- Número de filas y columnas: Contiene 5,132 filas y 11 columnas

- ¿Qué es la base de datos?: Esta base de datos contiene datos clínicos de varios pacientes analizados para examinar la salud cardiovascular y la función renal, ayudando a evaluar el riesgo de enfermedades cardíacas, diabetes y función renal deteriorada. Su propósito es apoyar la investigación y el desarrollo de modelos predictivos de riesgo. 

- ¿Cómo se obtuvieron los datos?: Se obtuvieron a través de registros clínicos y análisis de laboratorio recopilados para estudios de salud predictivos.

**Descripción de columnas.**

| **Nombre de columna** | **Tipo de dato** | **Descripción** | **Ejemplo** **de valor** **** |
| --- | --- | --- | --- |
| Index / ID | Numérico (int) | Número de identificación o índice de registro de cada paciente en el conjunto de datos. |  1 |
| Age | Numérico (int) | Edad del paciente en años. Factor de riesgo importante, ya que la probabilidad de diabetes aumenta con los años. | 26 |
| Gender | Texto (str) | Indica el sexo biológico del paciente (`M` para Masculino, `F` para Femenino). | M |
| BMI | Numérico (`float`) | Índice de Masa Corporal que relaciona la altura y el peso para evaluar sobrepeso u obesidad. | 23 |
| Chol | Numérico (`float`) | Nivel total de colesterol presente en la sangre (mg/dL). | 3.7 |
| TG | Numérico (`float`) | Nivel de triglicéridos o tipos de grasa presentes en la sangre (mg/dL). | 1.4 |
| HDL | Numérico (`float`) | Colesterol "bueno" que ayuda a transportar el exceso de colesterol desde los tejidos de vuelta al hígado. | 1.1 |
| LDL | Numérico (`float`) | Colesterol "malo" que puede causar acumulación de placa en las arterias. | 2.1 |
| Cr | Numérico (`float`) | Creatinina, producto de desecho del metabolismo muscular excretado por los riñones (mg/dL). | 62 |
| BUN | Numérico (`float`) | Nitrógeno ureico en sangre, utilizado para evaluar la función renal (mg/dL). | 4.5 |
| Diagnosis | Numérico (int) | Variable objetivo que indica el resultado clínico del diagnóstico. -Negativo/Sin diabetes=0 -Positivo/Con diabetes=1 | 0 |

