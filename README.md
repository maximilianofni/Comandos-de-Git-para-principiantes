# Comandos de Git para principiantes

En este repositorio, encontrarás una lista de comandos útiles para aquellos que estén empezando a trabajar con Git.

# Instalación de Git

Antes de empezar a utilizar Git, necesitas instalarlo en tu computadora. Puedes encontrar información sobre cómo hacerlo en el siguiente enlace: https://git-scm.com/

# Configuración de Git

Una vez que hayas instalado Git, es necesario realizar los siguientes dos comandos para poder hacer commits a un repositorio de GitHub o Gitlab:

    git config --global user.name "Nombre del Usuario"

    git config --global user.email "email@example.com"

Estos dos comandos son para configurar el nombre de usuario y la dirección de correo electrónico que se utilizará para hacer commits.

     git config user.name
    
     git config user.email
     
Estos dos comandos son para verificar el nombre de usuario y la dirección de correo electrónico que se configuro para hacer commits.

# Comandos útiles de Git

lista de comandos útiles para trabajar con Git:
    
    git init: Inicia un nuevo repositorio de Git.
    
    git clone "link de repositorio a clonar"
    
    git add .: Agrega un archivo al área de preparación.
    
    git commit - m "comentario": Guarda los cambios en el repositorio.
    
    git status: Muestra el estado actual del repositorio.
    
    git log: Muestra un historial de los commits realizados.
    
    git branch "nombre de la rama ": Crea una nueva rama de trabajo.
    
    <rama a> git merge " rama b": Combina dos ramas de trabajo, en este ejemplo todo lo de la "rama b" se copiar a la "rama a"
