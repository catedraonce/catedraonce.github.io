0. abrir terminal y hacer cd catedraonce.github.io (para María, que no se entera)

**cd catedraonce.github.io**

1. Realizar un `git pull` desde la raíz del repo para bajar posibles modificaciones por parte de otras personas. Poner en Terminal: git pull

**git pull**

2. Realizar los cambios necesarios en los documentos Markdown (.md) que componen el proyecto, añadiendo nuevos si es necesario.


3. Compilar y comprobar en local si los cambios han sido satisfactorios con la orden:

   ```
**mkdocs serve**
   ```
   Esto arrancará un servidor [web](http://127.0.0.1:8000), y utilizando vuestro navegador podréis observar los cambios en

   ```
   http://127.0.0.1:8000
   ```
el archivo mkdocs.yml tiene el arbol de navegación, solo tocar nav: para modificarlo
4. Si todo ha ido bien y es de vuestro gusto, abrir un nuevo terminal y meterme en cd catedraonce.github.io. Hacer git status: muestra ficheros modificados

hacer 

**git commit -a -m "Mensaje del motivo del cambio"**
 
hacer git push para que los cambios se vayan al repo

git push

5. Renderizar el contenido y subirlo a Github Pages utilizando en el terminal:

   ```
mkdocs gh-deploy
   ```
   Si todo ha ido bien, veréis en la [web](https://catedraonce.github.io/) los mismos cambios y contenidos que visualizasteis en local.


