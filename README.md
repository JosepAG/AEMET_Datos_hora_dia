# AEMET_Datos_hora_dia
Programa para ejecutar todos los dias y extraer datos diarios AEMET hora

Ejecutable AEMET_MEJORA.py, la configuracion de las estaciones a extraer datos se definene en Configuracion_Estaciones/Prova.txt, 
añadir lineas con más estaciones a traves de su nombre, ejemplos para Prova.txt:
  "3576X"
  "8416Y"

Los archivos extraidos se situaran en la carpeta Datos_Guardados con el formato: 
  "Datos_Guardados/AEMET"+" "+Nombre_tiempo[0:10]+" "+Nombre_ubi+" "+Estation+".csv"
  
  
 
 
 
 Crear rutina en el sistema operativo o el env elegido para ejecutarlo diariamente a la misma hora.
 
 En caso de caducidad en api_key dirigirse a https://opendata.aemet.es/centrodedescargas/altaUsuario? y solicitar.
 Cambiar en la variable querystring en AEMET_MEJORA.py

