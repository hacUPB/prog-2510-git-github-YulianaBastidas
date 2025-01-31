[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/3WK28ho-)
# Bitácora
Nombre del estudiante:  Yuliana Bastidas Lucero

Id.: 000459993


# Archivo Readme Punto Numero 5

## Breve descripcion del proyecto

El proyecto es repositorio que hace una recopilacion de como utilizar la consola con el fin de crear directorios y archivos. Tambien explica como utilizar la tecnologia de git para tener un manejo de versiones, la forma en la que se explica como usar git es con git bash y como sus comandos en la consola pueden ser usados para crear repositorios, hacer commits y subir cambios en un repositorio remoto. 

## Pasos para clonar y ejecutar el proyecto

1. Entrar en la carpeta en la que se quiere clonar el proyecto
2. Copiar la URL del repositorio desde git hub
3. Utilizar el comando de git clone y pegar la url como argumento de este comando
4. Entrar desde el explorador de archivos a donde se clono el repositorio para poder visualizar el proyecto
5. Entrar en la carpeta docs 
6. Abrir el archivo programa1.py y ejectuarlo en un IDE compatible con Python

## Enlace a archivos de docs

Para poder revisar la documentacion del proyecto porfavor ingresar a la carpeta [Docs](https://github.com/hacUPB/prog-2510-git-github-YulianaBastidas/edit/main/mi_proyecto/docs). En esta carpeta se encontraran los siguientes archivos:

1. [uso_consola](https://github.com/hacUPB/prog-2510-git-github-YulianaBastidas/blob/main/mi_proyecto/docs/uso_consola.md)
2. [repositorio_local](https://github.com/hacUPB/prog-2510-git-github-YulianaBastidas/blob/main/mi_proyecto/docs/repositorio_local.md)
3. [repositorio_remoto](https://github.com/hacUPB/prog-2510-git-github-YulianaBastidas/blob/main/mi_proyecto/docs/repositorio_remoto.md)

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

Sintaxis básica:
* coincide con cualquier número de caracteres.

? coincide con un solo carácter.

** coincide con cualquier número de directorios.

/ al inicio indica que el patrón es relativo al directorio del .gitignore.

(#) se usa para comentarios.

Ubicación:
Generalmente en la raíz del proyecto, pero puede estar en subdirectorios.

También existe un .gitignore global para aplicar reglas a todos los repositorios.

Consideraciones:
Si un archivo ya está en el repositorio, añadirlo al .gitignore no lo excluirá. Debes usar git rm --cached <archivo>.

Solo afecta a archivos no rastreados o nuevos.