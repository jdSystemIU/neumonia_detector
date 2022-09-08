Hola! Bienvenido a la herramienta para la detección rápida de neumonía.

A continuación le explicaremos cómo empezar a utilizarla

Requerimientos necesarios para el funcionamiento:

-Tener en funcionamiento docker
 Luego dirigirse al CMD y seguir las siguientes instrucciones:
- git clone https://github.com/jdSystemIU/neumonia_detector/tree/master
- docker build -t python:latest .
- docker run -it --rm -e DISPLAY=host.docker.internal:0 --net host python bash
- curl -O https://drive.google.com/u/0/uc?id=1JpGyx1rnblGaFROWm4IqOPMUn7mY6Bih&export=download&confirm=t&uuid=433c5583-2a11-40ee-844e-a01b1090cd50
- python main.py
----------------------------------------------------------------------------------

Uso de la herramienta:

- Ingrese la cédula del paciente en la caja de texto
- Presione el botón 'Cargar Imagen', seleccione la imagen del explorador de archivos
del computador
- Presione el botón 'Predecir' y espere unos segundos hasta que observe los resultados
- Presione el botón 'Guardar' para almacenar la información del paciente en un archivo excel
con extensión .csv
- Presione el botón 'PDF' para descargar un archivo PDF con la información desplegada en la interfaz
- Presión el botón 'Limpiar' si desea cargar una nueva imagen
