# Tendencias de búsqueda sobre salud mental en España (2004-2025)

## Descripción general

* **Nombre:** Mental Health Search Trends in Spain 2004-2025 (mental\\\_health\\\_spain\\\_final.csv)
* **¿Qué es?** Serie de tiempo mensual con el interés de búsqueda en internet en España de términos relacionados con salud mental (ansiedad, depresión, terapia online, ataques de pánico y estrés). Permite estudiar cómo ha cambiado la preocupación por estos temas a lo largo de los años, por ejemplo antes y después de la pandemia. Es útil en salud pública y salud mental digital.
* **¿Cómo se obtuvieron los datos?** Por registros de tendencias de búsqueda (tipo Google Trends), con valores relativos de 0 a 100, donde 100 es el mes de mayor interés dentro del periodo. No son conteos de personas ni diagnósticos. *(Confirmar la fuente exacta en la ficha de Kaggle.)*
* **Fuente / URL:** https://www.kaggle.com/datasets/wildina/mental-health-search-trends-in-spain-20042025
* **Filas x columnas:** 262 filas x 8 columnas
* **Formato:** CSV (\~9.3 KB)
* **Periodo:** marzo de 2004 a diciembre de 2025, un registro por mes
* **Valores nulos:** ninguno

## Descripción de columnas

|Columna|Tipo de dato|Descripción|Ejemplo|
|-|-|-|-|
|date|Fecha (str, AAAA-MM-DD)|Primer día del mes al que corresponde el registro|2004-03-01|
|anxiety|Numérico (int)|Interés relativo de búsqueda del término "ansiedad" (0-100)|41|
|depression|Numérico (int)|Interés relativo de búsqueda de "depresión" (0-100)|73|
|online\_therapy|Numérico (int)|Interés relativo de búsqueda de "terapia online" (0-100)|0|
|panic\_attacks|Numérico (int)|Interés relativo de búsqueda de "ataques de pánico" (0-100)|41|
|stress|Numérico (int)|Interés relativo de búsqueda de "estrés" (0-100)|35|
|anxiety\_diff|Numérico (float)|Cambio de anxiety respecto al mes anterior|-2.0|
|online\_diff|Numérico (float)|Cambio de online\\\_therapy respecto al mes anterior|0.0|

## Relevancia biomédica

Aporta datos de salud pública y salud mental digital: permite analizar tendencias de ansiedad, depresión y estrés en una población y el auge de la terapia en línea (telesalud).

