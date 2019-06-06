# Analisis Exploratorio Y Curación de Datos

Repositorio para la materia de Análisis Exploratorio y Curación de Datos de #DiploDatos de FaMAF - UNC. Más info en esta [página](http://diplodatos.famaf.unc.edu.ar/analisis-y-curacion-de-datos/)

## Contenido

* Filminas en pdf
* Datos de práctico (carpeta `input`):
    * `wtageinf.csv`: datos para el ejercicio de tablas de peso
    * `pasos.json`: datos para el ejercicio de pasos por provincia
    * `kickstarter-projects/`: datos para los ejercicios de limpieza
* Notebooks de práctico (carpeta notebooks):
    * `Limpieza.ipynb`: Checklist y ejercicios de limpieza de datos
    * `Ejercicio-tablas.ipynb`: Ejercicio de tablas de peso

## La resolución de los Ejercicios se realizó con Anaconda 1.9.7/Jupyter 
## La resolución de los Ejercicios está en las mismas notebooks de los prácticos

## Ejecución

1. Clonar repositorio
* git clone https://github.com/marceleon/AYC-Practico.git
2. Moverse a la carpeta raiz del proyecto y generar nueva imagen
* cd AYC-Practico
* docker build -t ayc .
2. Instanciar imagen en un contenedor
* docker run -it --rm -p 8888:8888 ayc
3. Mostrará por consola el link de ingreso con un token de validación
[I 00:18:19.858 NotebookApp] The Jupyter Notebook is running at:
[I 00:18:19.858 NotebookApp] http://(9f82e7153437 or 127.0.0.1):8888/?token=e99eb5317fb2549248cf0dcc14af914e40929858ee901559
4. Ingresar en el navegador http://127.0.0.1:8888/?token=e99eb5317fb2549248cf0dcc14af914e40929858ee901559
5. IMPORTANTE: el token mostrado es un ejemplo, copiar el que resulta de la propia ejecución

