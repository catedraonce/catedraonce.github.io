1. Realizar un `git pull` desde la raíz del repo para bajar posibles modificaciones por parte de otras personas.

2. Realizar los cambios necesarios en los documentos Markdown (.md) que componen el proyecto, añadiendo nuevos si es necesario.

3. Compilar y comprobar en local si los cambios han sido satisfactorios con la orden:

   ```
   mkdocs serve
   ```

   Esto arrancará un servidor [web](http://127.0.0.1:8000), y utilizando vuestro navegador podréis observar los cambios en 

   ```
   http://127.0.0.1:8000
   ```

4. Si todo ha ido bien y es de vuestro gusto, hacer un `git commit` y un `git push` para que dichos cambios reviertan en el repo.

5. Renderizar el contenido y subirlo a Github Pages utilizando:

   ```
   mkdocs gh-deploy
   ```

   Si todo ha ido bien, veréis en la [web](https://catedraonce.github.io/) los mismos cambios y contenidos que visualizasteis en local.

