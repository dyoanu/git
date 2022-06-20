# Git Desarrollo Colaborativo

Esto es una guia creada con la finalidad de facilitar el entendimiento y aplicacion de la herramienta conocida como GIT, que se utliliza para el control de versiones de nuestro proyectos. Aqui veremos como configurar la misma, asi como tambien, cada una de sus opciones.

## Configuracion Inicial

Cuando inicializamos un repositorio por primera vez, podemos establecer el nombre de usuario y correo electronico, para identificarnos dentro del histrorial de cambios. 

Cuando queremos definir una configuracion de manera general, debemos utlilizar el parametro *--global* para indicar que dicha configuracion debe almacenarse en la carpeta del usuario y no en la carpeta local *.git/* del repositorio.

* **git init**: Inicializa un repositorio de GIT.
* **git config --global user.name** 'username' : Define el nombre del usuario.
* **git config --global user.name** 'email' : Define el correo electronico para las confirmaciones.


## Gestion del proyecto

Para sincronizar los cambios realizados en el proyecto, debemos tener en cuenta que se creamos en nuestra computadora el mismo utlizando el comando *git init*, vamos a tener que crearlo tambien en nuestro servidor remoto, como por ejemplo [GitHub](http://github.com).

En el caso que ya exista un repositorio remoto, simplemente debemos descargar el historial de cambios del mismo, pero indistintamente de como hayamos empezado, lo principal es estar pendiente de los cambios realizados en el servidor de GIT.

