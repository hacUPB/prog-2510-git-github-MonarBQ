# Como crear un repositorio local con Git

## ¿Que es Git?
Git es un sistema de control de versiones que le permite el rastreo de cambios en el codigo a los desarrolladores y es comúnmente utilizado con plataformas como GitHub.

## ¿Que es un repositorio?
Es un espacio donde se almacenan los archivos de un proyecto y su historial de cambios, puede ser local (en tu computadora) y remoto (en una plataforma en linea)

### ¿Como se crea un repositorio local?
Para crear un repositorio local con Git lo primero que hacemos es configurar Git con tu nombre de de usurio y tu correo, con los siguientes codigos:

- git config --global user.name (Tu nombre)
- git config --global user.email (Tu correo)

Lo siguiente es crear una carpeta para guardar tu repositorio, dentro de esa carpeta creas un directorio con el nombre que le desees poner a tu repositorio.
Despues te vas a ubicar dentro del repositorio y ejecutas el siguiente comando 

- git init

Con esto ya tendras tu repositorio creado y podras empezar a guardar tus cambios, enviar commits y ver el estado del repositorio con algunos codigos como:

- git status (Para ver el estado del repositorio)
- git add (Para mandar los cambios al stage)
- git commit -m "cambios" (Para guardar un commit)

  ![Ejemplo](~/Documents/prog-2510-git-github-MonarBQ/mi_proyecto/images/eb105ed6-b837-4892-8f5e-f1359b9d7785.jpg)


Y con esto ya puedes moverte y utilizar tu repositorio local.
