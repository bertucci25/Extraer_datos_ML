# Extraer datos de Articulos mas vendidos en MeLi

Script simple para obtener datos de cualquier categoria en la seccion "Mas vendidos" del unicornio amarillo. 

## Herramientas usadas:

- Python junto con la libreria BeautifulSoup, y los modulos requests y xlsxwriter.
- Excel.

### Funcion del script:

El script basicamente localiza las etiquetas HTML del sitio web y filtra de manera que solo sean escritos en la hoja de calculo el Precio y Titulo del item.

No todas las etiquetas pueden ser iguales, sin embargo en ML, esta relativamente estandarizado asi que no deberia tener problema en usarlo para cualquier categoria con 
seccion de "Mas vendidos".

Nota: para hacer que funcione correctamente el script se debe virtualizar el espacio donde estan ubicado los archivos .py 
¿Cómo hacerlo? : en el powershell ubicados en la carpeta del projecto escribimos: 
`virtualenv env` y luego escribimos `env/scripts/activate` 
se deben instalar las librerias/modulos, lo podes hacer con el archivo del repo requirements.txt y el comando `pip install -r requirements.txt` 
para hacer correr el script tenemos que ejecutarlo desde la poweshell con `python cargar_datos_excel.py`

¿Aun no estas canchero con la linea de comandos? Puedes leer esta guía practica del sitio web Programming Historian haciendo click [acá](https://programminghistorian.org/es/lecciones/introduccion-a-powershell)





