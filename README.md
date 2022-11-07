# Examen DESPLIEGUE DE APLICACIONES WEB - 2º DAW
## Documentación de los ejercicios

Primero creo un repositorio nuevo en Github con el nombre **libro** y lo 
clono en la carpeta en la que voy a trabajar.

Compruebo que todo se ha copiado correctamente y todos los archvios han sido clonados
al repositorio local.

Creo el fichero **indice.txt** y escribo lo siguiente:
*Capítulo 1: Introducción a Git*
*Capítulo 2: Flujo de trabajo básico*
*Capítulo 3: Repositorios remotos*

Compruebo el estado del repositorio con un git status.

Añado el fichero con *git add .* y vuelvo a comprobar el estado del repositorio 
con *git status*.

Hago un *git commit* para indicar que he añadido el índice del libro.

Añado más capitulos al indice.txt y vuelvo a hacer un commit informando de los cambios.

Ahora creo la carpeta capítulos y creo el archivo *capitulo1.txt*.

Hago un commit informando de ello.

Repito este proceso con los 3 siguientes capitulos.

Añado el capitulo 5 al fichero *indice.txt* y hago un *git commmit* informando de ello.

Creo la rama *bibliografia*

Creo el fichero *capitulo4.txt* y hago un commit diciendo que acabo de crear este fichero.

Cambio a la rama *bibliografia* con *git checkout*.

Creo un fichero *bibliografia.txt*. Hago un commit informando del cambio.

Fusiono las ramas master y bibliografia situandome en la rama master y 
haciendo un *git merge*.

Muestro la captura del repositorio y los cambios hechos.

Borro la rama *bibliografia* con *git branch -d bibliografia* y la vuelvo a crear con 
*git branch bibliografia*.

Me cambio a la rama bibliografia con *git checkout bibliografia*.

Modifico el fichero *bibliografia.txt* desde la rama bibliografia y hago un commit.

Cambio a la rama master con *git checkout master*.

Cambio el fichero *bibliografia.txt* y añado otras referencias y de nuevo hago commit informando.

Fusiono las dos ramas con *git merge bibliografia*.

Para resolver el conflicto borro los cambios hechos en la rama bibliografia y cambio
el archivo desde la rama master con las utlimas modificaciones pedidas.

Finalmente hago un commit diciendo que he resuelto el conflicto.









