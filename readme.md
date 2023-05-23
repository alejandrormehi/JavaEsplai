
# Ejercicio 1 de repositorios  

1.1 Primero hemos creado un directorio llamado repo01 

![Error al cargar la img](./img/Screenshot_1.jpg "Primer paso para trabajar con repositorios")

+ Hemos creado la carpeta repo1, cometimos el error al llamarla “repo1” y no “repo01”  
+ Usamos el comando “mv” para cambiar el nombre, sin embargo lo habiamos hecho manualmente  
+ Con el comando “ls” vemos que el nombre ya esta cambiado

![Error al cargar la img](./img/2.jpg "Segundo paso para trabajar con repositorios")

+ Con el comando “git init nombre_carpeta” hemos convertido a la carpeta “repo01” a un repositorio GIT.

+ Hay dos formas de comprobar que estamos dentro de un repositorio:
  
  + La primera es ver la carpeta oculta dentro del nuevo repositorio llamado “.git”:
  
![Error al cargar la img](./img/3.jpg "Tercer paso para trabajar con repositorios")

+ La segunda es entrando desde la terminal GIT bash a la carpeta del repositorio y ver que en el nombre nos aparece una nomenclatura adicional titulada “master”, eso indica que estamos en la rama principal del repositorio.

![Error al cargar la img](./img/4.jpg "Tercer paso para trabajar con repositorios")

1.2 Creacion MarkDown

![Error al cargar la img](./img/5.jpg "Tercer paso para trabajar con repositorios")

+ Primero hemos creado el archivo MarkDown

1.3 Ahora añadiremos el fichero a la staging area

  1. Primero vemos el estado del repositorio con la comanda **git status**. Aqui comprobamos la existencia y ubicacion del archivo markdown.
![Error al cargar la img](./img/gitStatus.jpg "Tercer paso para trabajar con repositorios")

  2. Luego hemos añadido con el comando **git add .** todos los directorios, archivos, etc, del directorio. Hemos usado el "." para añadir todo.  
   ![Error al cargar la img](./img/gitAdd.jpg "Tercer paso para trabajar con repositorios").

  3. Ahora con un **git status** podemos ver el estado actual y como se diferencia del estado anterior.
   ![Error al cargar la img](./img/git6.jpg "Tercer paso para trabajar con repositorios")
  4. Posteriormente usamos el comando **git commit -m "nombre_archvios"** y subimos al Git nuestro proyecto
![Error al cargar la img](./img/git7.jpg "Tercer paso para trabajar con repositorios")
Ahora nuestro fichero se encuenta en la fase de "Local Repository"

+ Aqui abajo podemos ver el historial de los commits hechos con **git log"**
    ![Error al cargar la img](./img/git8.jpg "Tercer paso para trabajar con repositorios")

1.4 Subiendo con Git Push

+ Intentamos subir nuestro archivo mediante el comando **git push** ,  pero este no nos deja debido a que no tenemos un repositorio remoto configurado.
![Error al cargar la img](./img/gitPush1.jpg "Tercer paso para trabajar con repositorios")

+ Para hacerlo correctamente tenemos que crear un repositorio en GitHub y enlazarlo a nuestro repositorio local

1.5 Usamos **git remote -v**
![Error al cargar la img](./img/gitRemote.jpg "Tercer paso para trabajar con repositorios")

+ No nos aparece nada debido a que no hay ningun repositorio asociado.
1.6 Creamos un repositorio en GitHub llamado repo01

![Error al cargar la img](./img/repoHub.jpg "Tercer paso para trabajar con repositorios")

+ Vemos que en la terminal se ha actualizado de forma automática la conexion con GitHub
![Error al cargar la img](./img/gitRepo1.jpg "Tercer paso para trabajar con repositorios")

1.7 Ahora volvemos a usar el comando **git remote -v**  

![Error al cargar la img](./img/gitRemote2.jpg "Tercer paso para trabajar con repositorios")

+ Ahora vemos que si que nos aparece más informacion que antes 