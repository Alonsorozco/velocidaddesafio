Desafío - Velocidad de escape


● Para realizar este desafío debes haber estudiado previamente todo el material


disponibilizado correspondiente a la unidad.
● Una vez terminado el desafío, comprime la carpeta que contiene el desarrollo de los
requerimientos solicitados y sube el .zip en el LMS.


● Desarrollo desafío: Grupal
La velocidad de escape de un planeta (la velocidad mínima necesaria para poder salir de un
planeta) está dada por la siguiente ecuación.
V e = √2gr

Donde:
● g: Es la gravedad del planeta.
● r: Es el radio del planeta (en metros).

Se pide crear el programa escape.rb donde el usuario ingrese la gravedad y el radio, y
como resultado obtenga la velocidad de escape (ocupar la fórmula).
● Desarrollar el diagrama de flujo antes del programa.
● Verificar el funcionamiento con los datos de la Tierra:
○ g = 9.8

mts
seg
2
○ r = 6371 km

○ Respuesta: 11174, 6 ​aproximadamente.
s
mts

● Importante: Utilizar ARGV en lugar de gets.
○ El primer argumento será g.
○ El segundo será r.
El programa debe poder ejecutarse como: ruby escape.rb 9.8 6371.
