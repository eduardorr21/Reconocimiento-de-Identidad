# Reconocimiento-de-Identidad
este Software de Reconocimiento de Identidad fue desarrollado pensando en las personas, pequeños negocios y empresas que contratan a personas y tratan con ellas y todos los días tenemos que lidiar con la delincuencia que siempre se encuentra en el anonimato

# CRIMINALES QUE PUEDE DETECTAR
- http://www.recompensas.pe/profugo/frank-gino-rosales-yupanqui
- http://www.recompensas.pe/profugo/julio-claudio-huayaney-giraldo
- http://www.recompensas.pe/profugo/alberto-chavez-bello
- http://www.recompensas.pe/profugo/yhider-yhimer-martel-tarazona
- http://www.recompensas.pe/profugo/pedro-julian-alarcon-ramos
- http://www.recompensas.pe/profugo/pedro-castillejo-tarazona
- http://www.recompensas.pe/profugo/cynthia-melina-campos-velezmoro
- http://www.recompensas.pe/profugo/dante-ccopa-ayala
- http://www.recompensas.pe/profugo/miguel-angel-santos-perez
- http://www.recompensas.pe/profugo/cerilo-saavedra-principe
- http://www.recompensas.pe/profugo/martin-ignacio-olavide-gomez-de-la-torre
- http://www.recompensas.pe/profugo/carlos-almilcar-flores-infante
- http://www.recompensas.pe/profugo/rolando-mejia-gallegos
- http://www.recompensas.pe/profugo/juan-de-mata-morales-vacas
- http://www.recompensas.pe/profugo/anthony-mayer-torres-izquierdo
- http://www.recompensas.pe/profugo/yossi-amelia-rodriguez-benavides
- http://www.recompensas.pe/profugo/maria-isabel-henostroza-maza
- http://www.recompensas.pe/profugo/nelio-j-lopez-pardo
- http://www.recompensas.pe/profugo/lucia-elena-ramirez-salinas
- http://www.recompensas.pe/profugo/bernabe-huayhua-urbano
- http://www.recompensas.pe/profugo/socrates-veramendi-salgado
- http://www.recompensas.pe/profugo/elmer-jorge-inocente-agurto
- http://www.recompensas.pe/profugo/dionicio-wilfredo-cisneros-hilario
- http://www.recompensas.pe/profugo/segundo-alejandro-edquen-fernandez
- http://www.recompensas.pe/profugo/ernesto-fidel-perez-gonzales
- http://www.recompensas.pe/profugo/danny-raphael-ochoa-cucho
- http://www.recompensas.pe/profugo/gabino-saul-ayala-cabana
- http://www.recompensas.pe/profugo/julio-christian-yataco-alvarado
- http://www.recompensas.pe/profugo/alfredo-procopio-leiva-romero
- http://www.recompensas.pe/profugo/martha-elizabeth-lozada-touzett
- http://www.recompensas.pe/profugo/alejandrina-pillco-canal
- http://www.recompensas.pe/profugo/deomides-romero-salvatierra
- http://www.recompensas.pe/profugo/jesus-manuel-pinzas-gonzales
- http://www.recompensas.pe/profugo/francisco-ortiz-portal
- http://www.recompensas.pe/profugo/noe-jesus-manrique-alonzo
- http://www.recompensas.pe/profugo/jonnatha-yan-pool-felices-alcarraz

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

