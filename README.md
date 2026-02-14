## telecom-analysis
Analisais de datos en ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.


# Objetivo

El objetivo de la empresa es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

Datasets utilizados

plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).
Etapas del análisis.

Integrar y limpiar bases de datos provenientes de tres fuentes distintas.
Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.
Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.
Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.
Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.
Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
Documentar todo el proceso en un Jupyter Notebook, junto con un README reproducible para subirlo a GitHub.
Ejecutar

Abrirlo en Google Colab.
Guía de reproducción

Descargar los archivos de datos en la carpeta datos/
Instalar las librerías: pip install pandas numpy matplotlib
Ejecutar el notebook celda por celda
Los resultados aparecerán en la misma secuencia
