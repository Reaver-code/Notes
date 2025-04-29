Aquí tienes una lista de los comandos de Git más comunes, organizados por categorías:

### Configuración Inicial

- `git config --global user.name "Tu Nombre"`: Configura tu nombre de usuario.
- `git config --global user.email "tuemail@ejemplo.com"`: Configura tu correo electrónico.
- `git config --global color.ui auto`: Configura el uso de colores en la salida de Git.
- `git config --list`: Muestra la configuración actual de Git.

### Comandos Básicos

- `git init`: Inicializa un nuevo repositorio Git.
- `git clone [URL]`: Clona un repositorio remoto en tu máquina local.
- `git status`: Muestra el estado de los archivos en el directorio de trabajo.
- `git add [archivo]`: Añade un archivo al área de preparación (staging).
- `git commit -m "Mensaje del commit"`: Guarda los cambios en el repositorio con un mensaje descriptivo.
- `git log`: Muestra el historial de commits.
- `git diff`: Muestra las diferencias entre archivos no confirmados.
- `git diff --staged`: Muestra las diferencias entre archivos que están en el área de preparación.

### Trabajando con Ramas

- `git branch`: Lista todas las ramas en el repositorio.
- `git branch [nombre]`: Crea una nueva rama.
- `git checkout [nombre de rama]`: Cambia a la rama especificada.
- `git checkout -b [nombre de rama]`: Crea una nueva rama y cambia a ella.
- `git merge [nombre de rama]`: Fusiona la rama especificada en la rama actual.
- `git branch -d [nombre de rama]`: Elimina la rama especificada.

### Comandos Remotos

- `git remote add origin [URL]`: Conecta el repositorio local a un repositorio remoto.
- `git remote -v`: Muestra los repositorios remotos configurados.
- `git fetch [remote]`: Descarga los cambios desde un repositorio remoto, sin fusionarlos.
- `git pull [remote]`: Descarga y fusiona los cambios desde un repositorio remoto.
- `git push [remote] [rama]`: Sube los commits locales a un repositorio remoto.

### Deshacer Cambios

- `git reset [archivo]`: Quita un archivo del área de preparación.
- `git reset --hard [commit]`: Restaura todo el directorio de trabajo al estado de un commit específico.
- `git revert [commit]`: Crea un nuevo commit que deshace los cambios de un commit específico.

### Guardar Trabajo en Proceso

- `git stash`: Guarda los cambios no confirmados temporalmente.
- `git stash pop`: Restaura los cambios guardados en el stash y los elimina de la pila de stash.
- `git stash list`: Muestra la lista de stashes guardados.
- `git stash drop`: Elimina un stash especificado de la pila.

### Inspeccionar y Comparar

- `git show [commit]`: Muestra información sobre un commit específico.
- `git log --oneline`: Muestra el historial de commits en una línea por cada uno.
- `git diff [branch1] [branch2]`: Muestra las diferencias entre dos ramas.

### Etiquetas (Tags)

- `git tag`: Lista todas las etiquetas en el repositorio.
- `git tag [nombre]`: Crea una nueva etiqueta con el nombre especificado.
- `git tag -d [nombre]`: Elimina una etiqueta.
- `git push origin [nombre]`: Sube una etiqueta específica a un repositorio remoto.

### Otros Comandos Útiles

- `git rm [archivo]`: Elimina un archivo del directorio de trabajo y del área de preparación.
- `git mv [archivo1] [archivo2]`: Mueve o renombra un archivo.
- `git clean -f`: Elimina archivos no rastreados del directorio de trabajo.
- `git bisect start`: Comienza la búsqueda binaria para encontrar el commit que introdujo un error.
- `git rebase [branch]`: Reaplica commits en la parte superior de otra rama base.

Esta lista cubre muchos de los comandos esenciales que usarás al trabajar con Git. ¡Espero que te sea útil!