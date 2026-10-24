# Almacenamiento DVC de "Defiende el servidor"

Este repositorio **no es código**: es el almacenamiento (remote) de DVC del proyecto
https://github.com/davidbrinez30/defiende-el-servidor-unsw-nb15

Contiene los objetos direccionados por contenido (`files/md5/..`) de:

- los datos originales de UNSW-NB15 (versión 1 de los datos) y los datos preparados con sus particiones (versión 2);
- los modelos completos de cada experimento y los paquetes de las versiones v1 y v2.

Se usa como remote HTTP de solo lectura (`.dvc/config` del proyecto):

    https://raw.githubusercontent.com/davidbrinez30/defiende-el-servidor-dvc-storage/main

No necesita credenciales. Desde el repositorio de código: `dvc pull` (ver su README). Para usarlo como carpeta local,
clónalo y `dvc remote add -d respaldo <carpeta>`.
