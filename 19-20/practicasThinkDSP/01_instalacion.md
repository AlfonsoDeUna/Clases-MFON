### INSTALACIÓN DEL ENTORNO PARA REALIZAR LAS PRÁCTICAS CON THINKDSP

## INTRODUCCIÓN
ThinkDSP es un libro y prácticas de python en Jupyter para estudiar procesamiento digital de la señal.

## REQUISITOS
    jUPYTER Y PYTHON

## DESCARGAR THINKDSP
https://github.com/AllenDowney/ThinkDSP/archive/master.zip

## DESCARGAR ANACONDA e instalar ANACONDA
https://www.anaconda.com/distribution/#download-section

### Añadir a la variable del entorno las siguientes rutas:
* directorio donde hayas instalado anaconda ejemplo: *c:\programs\anaconda3*
* directorio de los scripts: *c:\programs\anaconda3\scripts*
* directorio de las librerias *c:\programs\anaconda3\bin\library*

**nota** Busca la ruta donde has instalado ANACONDA entra en la carpeta y busca otra carpeta que se llama script. Copia la ruta
Añadir a la variable de entorno Path

## EXTRAER TODO EL CONTENIDO DE ZIP THINKDSP EN UNA CARPETA
```
c:\ThinkDSP
```

## CREACIÓN DEL ENTORNO A TRAVÉS DE CONDA

Ir al directorio ThinkDSP y crear el entorno
```
c:\> cd ThinkDSP
c:\> conda env create -f environment.yml
```
Por último activar el entorno
```
c:\> activate ThinkDSP
```

y ejectuar en el navegador http://127.0.0.1:8888


