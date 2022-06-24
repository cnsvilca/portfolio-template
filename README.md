# Trayecto de Formación: FullStack Web Developer :school:

## :books: Comandos utiles para usar GIT
### :computer: Area de trabajo

*Eliminar archivo*

```bash
    git rm <nombre del archivo>
```
*recuperar archivos eliminados*

 ```bash
    git restore --staged <nombre del archivo>
    git restore <nombre del archivo>
 ```

 *ver los cambios realizados*
 ```bash
    git status
 ```
 ### :floppy_disk: Area de Staging
 *mover archivos y modificaciones al area de staging*
 ```bash
    git add . 
 ```

### :computer: Area repositorio local

*mover los archivos y modificaciones al repositorio local (checkpoint)*
```bash
    git commit -m "first commit: descripcion"
 ```

*bajar los cambios al repositorio local*
```bash
    git pull <nombre del repositorio remoto>
 ```
*ver el historial de commits dos opciones*
```bash
    git log
    git log --oneline
 ```

 ### :cloud: Area repositorio remoto

 *subir los cambios al repositorio remoto*
 ```bash
    git push -u origin main
 ```

 ### :seedling: Trabajar con Ramas 

*Crear una nueva rama*
```bash
    git branch <nombre de nueva rama>
 ```

 *listar las ramas*
 ```bash
    git branch -v
 ```

 *cambiar la rama actual*
 ```bash
    git checkout <nombre de la rama>
 ```

### :link: Enlaces utiles
- [guia markdown](https://www.markdownguide.org/basic-syntax/)
- [emojis markdown](https://www.webfx.com/tools/emoji-cheat-sheet/)
- [google fonts](https://fonts.google.com)
- [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

:package: **Módulo 1: Entorno de trabajo y control de versiones**

## Introducción
Hola! :smile: Éste es el primer proyecto con el que daremos nuestros primeros pasos en el desarrollo de software. Nuestro camino iniciará con Visual Studio Code, Git y Github, a lo largo de este módulo nos familiarizaremos con este entorno de trabajo. Recuerda que pronto armaremos equipos de desarrollo así que te recomendamos que te vayas preparando. Tú y tu equipo experimentarán situaciones donde deberán coordinarse y cooperar para tener éxito, esto te dará un pequeño vistazo de lo que hay allí afuera.

Sin más que decir, te deseamos éxitos en este camino de formación! :clap:

## Instalación

Para iniciar con este proyecto debes tener lo siguiente:

- Visual Studio Code Instalado
- Git Instalado
- No necesitas cuenta de GitHub pero la necesitarás mas adelante. Te recomiendo que te vayas registrando.

## Iniciar el proyecto

Una recomendación nuestra es que uses la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) para VS Code. Esta extensión te permite iniciar un servidor en tiempo real y ver los cambios que se hagan en el código.

## Manejo de problemas

Si tienes alguna duda o problema que no se puede resolver en el proyecto te animamos a que lo consultes con los instructores. El problema que enfrentas puede sucederle a otro compañero.

## Recursos

Si te interesa saber más del avatar utilizado en este proyecto, puede ver [Open Peeps](https://www.openpeeps.com) donde podrás personalizar y descargar tu propio avatar con el mismo estilo y gratis.