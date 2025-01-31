# Como crear un repositorio remoto

# Pasos para crearlo 
Para crear un repositorio en GitHub, entramos a este y vamos a perfil, ahí nos dirigimos a repositorios y damos click en new, agregamos nombre del repositorio, descripción (opciona)l, elegimos si lo queremos público o privado y damos click en crear repositorio, ahora necesitamos  sincronizarlo con nuestro repositorio local, para esto utilizamos los comandos de git push y git pull, que sirven para subir los cambios de del directorio local al directorio remoto y para traer los cambios del repositorio remoto a mi repositorio local  respectivamente
### Ejemplo de como crear repositorio remoto 
Paso 1. entramos a GitHub-perfil-repositorios


![alt text](<../images/como crear repositorio remotoGitHub.jpg>)


Paso 2. Lo creamos dando click en NEW, agregamos nombre del repo, descripción (opcional) y le damos en crear repositorio


![alt text](<../images/caracteristicas del nuevo repo remoto.jpg>)



Paso 3. Debemos sincronizar nuestro repositorio remoto con el repositorio local, para esto copiamos link del repo y lo clonamos en la carpeta desea en nuestro computador


![alt text](<../images/clonación de repo.jpg>)

 
Paso 4. Sinconización completa 


![alt text](<../images/sincornización repo remoto con repo local.jpg>)




### Investigación archivo .gitignore

Un archivo .gitignore es un archivo de texto usado en proyectos con Git para especificar qué archivos o directorios no deben ser rastreados ni incluidos en el repositorio. Su función principal es excluir archivos innecesarios, temporales o sensibles, como:

Archivos generados por el sistema o editores (.DS_Store, Thumbs.db).

Configuraciones locales (.vscode/, .idea/).

Dependencias (node_modules/).

Archivos binarios o compilados (.class, .o).

Ventajas:
Mantiene el repositorio limpio: Evita que archivos irrelevantes se suban.

Mejora el rendimiento: Reduce el tamaño del repositorio.

Evita conflictos: Excluye archivos que pueden variar entre entornos.
