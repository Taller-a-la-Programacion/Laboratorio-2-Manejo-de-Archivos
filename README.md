# Manejo de archivos

# Manejo de Archivos


El siguiente laboratorio consiste en una serie de ejercicios para practicar el desarrollo de programación en sintaxis de Python, además de evaluación de conceptos vistos en clases anteriores.
El objetivo de este laboratorio está en el uso de y manipulación archivos y cadenas de texto, recuerde que en cada función que desarrollen agregar los comentarios (nombre, parámetros entrada, salida y restricciones), además, se reforzará el uso de los inputs para el manejo de menú.

## Ejercicio 1. Valor 10 puntos.
Escriba una función llamada totalizar(archivo, valorCol1, valorCol2) que tiene como parámetro de entrada el nombre del archivo, el valor de ambas columnas para totalizar, el resultado será imprimir su contenido totalizado según categoría especificada, el archivo tendrá una estructura separada por comas, ejemplo:

Ejemplo de contenido de un archivo (ejercicio1.txt):
lunes, comida, 20000
lunes, gasolina, 5000
martes, comida, 15000
martes, comida, 3500
miércoles, servicios, 4000
jueves, comida, 8500.5
jueves, gasolina, 10000

>>> totalizarArchivo(“archivo1.txt”, “lunes”, “comida”)
“Total para Lunes por concepto de Comida es: 20000 colones”

>>> totalizarArchivo(“archivo1.txt”, “martes”, “comida”)
“Total para Martes por concepto de Comida es: 18500 colones”


## Ejercicio 2. Valor 10 puntos.
Escriba una función llamada ordenarArchivos(archivo1, archivo2, archivo3) que reciba tres parámetros de entrada, el nombre de un archivo1, archivo2 y el nombre del nuevo archivo, este último tendrá el contenido ambos archivos ordenados de mayor a mejor. Evitar funciones built-in. Los datos de cada archivo serán del tipo numérico, entero y positivo, además existirá un número por línea. El archivo de salida se debe crear con el nombre del parámetro 3.

Ejemplo:
Archivo1.txt	Archivo2.txt	archivoSalida.txt
     22          	3            	3
     78	         99	            5
      5	         46	           22
	               89	           46
		                           78
		                           89
		                           99

>>> ordenarArchivos(“archivo1.txt”, “archivo2.txt”, “nuevoArchivo.txt”)
El contenido del nuevo archivo es: 
3, 5, 22, 46, 78, 89, 99

