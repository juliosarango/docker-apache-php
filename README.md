# docker-apache-php
Imagen docker de centos con php 5.6 y servidor web apache. Además oci8 como conector a bd oracle.
## Pasos para ejecutar el Dockerfile.
1. Bajar los paquetes rpm de la siguiente [dirección de oracle](http://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html)
o desde esta [carpeta de google drive](https://drive.google.com/drive/folders/0Bw_rVtdPfg_WcDZwRXFDei1SNFE?usp=sharing).
2. Ubicar estos archivos bajo la carpeta includes.
3. Ejecutar docker build -t some_name .
4. Ejecutar el contenedor con docker-compser up -d.
