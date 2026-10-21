# Validación de la práctica — 21 octubre 2026

Ejecutar los notebooks en orden: 1_limpieza_de_datos.ipynb, 2_eda_imdb.ipynb y 3_ejercicios_pandas_delitos.ipynb, desde la raíz del repositorio. El primero regenera data/delitos.csv y crea data/delitos_detalle.csv para conservar los subtipos; el tercero necesita esos resultados. Los CSV derivados se generan localmente, no se deben tomar los del fork como resultados de esta ejecución.

Se ejecutaron 37 + 26 + 8 = 71 celdas de código con IPython en el entorno del asistente, sin errores no controlados. Se conservaron salidas y figuras en los cuadernos. Trabajo realizado con asistencia de IA por solicitud del alumno; no acredita comprensión independiente.

Correcciones: se conservan faltantes en sumas enteramente ausentes; se filtra Homicidio doloso y Robo de vehículo automotor desde los datos detallados; se muestran todos los empates; el último año es parcial. Una proyección mensual multiplicada por 12 no equivale al total anual observado. Las tasas usan población fija de 2015 como ejercicio.

Resultados de los archivos históricos del curso: 617 registros de homicidio doloso en Colima en 2018; 187661 de robo de vehículo automotor en México en 2019. La pregunta sobre el municipio con más feminicidios NO puede responderse con esta fuente estatal; el notebook deja esa limitación explícita y muestra por separado el máximo estatal, sin confundir ambos niveles.

Fuentes: archivos originales de mendiolaleonel2002-debug/analisis_exploratorio. No se presentan estas cifras como estadísticas actuales.
