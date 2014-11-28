Tarea1
======

Aprendiendo a usar github

/git config --global user.name "Gerardo" 

/git config --global user.email "xxxxxx@fibertel.com.ar"

Generación de mi clave ssh:

/ssh-keygen

Abrirla con el editor
Copiarla en github

Empezar el proyecto:
Primero hay que ubicarse en la carpeta que será nuestro repositorio en la pc.

/git init

/git add miArchivo

/git commit -m "Comentario"

Elegir el repositorio con el que se va a trabajar (la clave ssh debe ser correcta sino da error)
/git remote add origin url

Traer contenido del repositorio en la web y lo pone en mi pc
/git pull origin master

Envia a la web los cambios realizados en mi pc
git push origin master
