# nephera
## README
Este es un ejemplo de un readme con lenguaje markdown.
Mediante la siguiente documentacion, procederemos a ver com realizar un buen 
archivo de **README**.

### Contenido
#####Proyecto Nephera
#####Comandos Git en Nephera
#####Un buen README
#####Otras consideraciones al momento de realizar un README

### Proyecto Nephera
El siguiente es un proyecto para realizar practicas con comandos Git, 
la idea de utilizar un proyecto fantasma que posiblemente pueda
ser implementado por algun lenguaje.
====================================================================
ATENCION SOLO CON FINES EDUCATIVOS - PRACTICOS
====================================================================

### Comandos Git en Nephera
Cuando se crea el proyecto en GitHub, se fue a la parte superior derecha 
la vista principal del usuario, en su lado izquierdo se encontraran 
una flecha invertida por la cual ingresaras a las opciones 
>ir a NEW REPOSITORY
luego procedes a hacer click y te enviara a la vista de formulario
para la creacion de nuevo repositorio.
Llenas los campos del formulario con datos como: nombre, seleccionar 
privacidad de repositorio [si este ser privado o publico], crear un 
README autogenerado y pulsar el boton aceptar o crear.
Y listo ya tienes el repositorio...
========================================================================

###### Comandos GIT
Para configurar tu equipo git debes ejecutar las siguientes:
'git config --global user.name "nombre de usuario"'
'git config --global user.email "correo electronico"'
luego crears una carpeta donde alojar el repositorio:
'mkdir [nombre del repositorio]'
ingresas en la carpeta:
'cd [nombre de carpeta]'
Luego pasas a clonarlo el repositorio en tu maquina local:
'git clone [enlace https del nuevo repositorio de tu cuenta GitHub]'
cuando termine de clonar, inicias dentro el repositorio:
'git init'
puedes crearte una rama para no trabajar sobre la rama master:
'git checkout -b [nombre de la rama]'
procedes a realizar o subir las modificaciones, en nuestro caso
subimos un archivo instrucciones.txt:
'echo "este archivo contendra informacion sobre intruscciones">>instrucciones.txt'
aniadimos a la rama que tenemos:
'git add .'
verificamos si se subieron los cambios correctamente:
'git status'
realizamos el primer commit:
'git commit -m "Primer Commit"'
luego subimos al repositorio en la nube:
'git push origin [nombre de la rama]'
y verificamos que se halla subido correctamente en el repositorio de la nube
mediante el navegador de preferencia.
==========================================================================

### Un buen README
Un README.md es un archivo que contiene las instrucciones - acciones 
a realizar por un usuario con el repositorio que esta trabajando.

Un **README** contiene: 
- INTRODUCCION
- INFORMACION DEL PROYECTO
- DOCUMENTACION
- INFORMACION EXTRA

En la __introduccion__ podemos obsrvar generalmente un resumen de lo que 
realiza el proyecto, generalmente debe estar escrita de forma breve y
clara.

En la __Informacion del Proyecto__ podemos encontrar informacion tecnica, 
respecto al estatis del proyecto, alcance, que tanto se ha avanzado, 
limitaciones, tecnologias, etc. de lo que respecta especificamente al 
proyecto.

En la __Documentacion__, encontraremos informacion sobre como poner en marcha
el proyecto, que archivos descargarse, como construir la base de datos,
configuraciones de rutas de inicio, etc.

En la __Informacion Extra__, existe informacion adicional que los usuarios
pueden utilizar para aclarar detalles que no hayan comprendido en el resto
del **README** o informacion de contacto como redes sociales, etc.

###### Otras Consideraciones al momento de realizar un README

Podemos encontrar consejos optimos al realizar un README eficiente:
1. El primer titulo siempre es el nombre del proyecto
2. El texto siguiente debe ser una descripcion simple del contexto del proyecto
3. Si se tienen un avance de una demo, puede agregarse como proyecto desplegado
4. Si se requiere agrega una lista con los pasos minimos que se necesitan para
	clonar exitosamente el proyecto.
5. Explica que debe ejecutarse para que sea posible instalarlo o instalar 
	dependencias necesarias
6. Agrega en lo posible imagenes que indiquen como se ve el proyecto luego de instalarse
7. Finaliza con notas o apuntes que quisieras agregar, fuentes, agradecimientos
	notas extras, imagenes, documentos, etc.
