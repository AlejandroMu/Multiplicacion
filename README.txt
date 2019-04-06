Configuracion
---------------------------------------------------
  En la carpeta src/main/resources se encuentra el archivo config.properties en donte se especifican las 
  rutas del los archivos donde estan las matrices y donde se va a guardar el resultado.

Formato para las matrices
----------------------------------------------------
#filas #columnas
# # # # # ...
.
.


Compilacion y execucion con FraSCAti script:
---------------------------------------------------
  frascati compile src/main/java multiplicacion
  frascati run src/main/resources/multiplicacion -libpath multiplicacion.jar -s operar -m run
