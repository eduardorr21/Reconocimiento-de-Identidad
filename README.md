# Reconocimiento-de-Identidad
este Software de Reconocimiento de Identidad fue desarrollado pensando en las personas, pequeños negocios y empresas que contratan a personas y tratan con ellas y todos los días tenemos que lidiar con la delincuencia que siempre se encuentra en el anonimato

# Requerimientos
- Python3
- Xampp

# Librerias Python usadas
- numpy==1.14.3
- opencv-contrib-python==3.4.1.15
- opencv-python==3.4.1.15
- mysqlclient==1.3.12
- image==1.5.24

# Uso

- Descomprimir el dataSet.rar que se encuentra en la carpeta dataSet/
- Elimiar el dataSet.rar
- Descargar la data de entrenamiento: https://drive.google.com/open?id=1NQh2345L40C53imEoHXPCgkZm2PG8bI5
- copiar y pegar en la carpeta recognizer/


# Incluir Nueva Data
1. importar el sql de la carpeta xampp/ a Mysql
2. ir a xampp\FormularioCriminales y con xampp correr formulario.php
3. Agregar con los campos del formulario
4. Si tiene una imagen del criminal, la extension debe ser "numero de id que sigue".jpg
5. Pegar la imagen en la carpeta modelos
6. Ejecutar dataSetImagen.py
7. Si va a usar la WebCam ejecutar dataSet.py
8. Para el entrenamiento ejecutar entrenador.py
9. Para la deteccion ejecutar deteccion.py

