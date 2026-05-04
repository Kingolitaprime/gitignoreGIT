1. ¿Para qué sirve el archivo .gitignore?
    sirve para decirle a git, que archivos si pueden usar o no. Al hacer que se ignorae se deja de rastrear sus cambio, evitando que aparezcan como archivos pendientes de subir, y mantiene el repositorio limpio sin ningun error
2. ¿Qué tipo de archivos es conveniente ignorar?
    Es sobretodo para ignorar datos importantes, y/o sensibles, en donde no se pueden compartir, carpetas de dependencia que son pesadas, archivos temporales y los que son generados de manera automatica que no son codigo fuente

3. ¿Un archivo ignorado se sube a GitHub?
    Si un archivo está en el .gitignore, Git no lo incluye en los commits. Por lo tanto, el archivo solo esta en tu computadora local y nunca se envían al servidor de GitHub.