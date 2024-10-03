# clase 06 - Bootcamp

## Para sacar un archivo de staging area y volverlo al working directory (solo se puede volver atras al principio)
```sh
 git rm --cached <nombre del archivo>
 git restore --staged <nombre del archivo>
 ```

### si tenes otro editor y lo queres cambiar a NANO
```sh
 git config --global core.editor nano
  git config --global core.editor "code --wait" (esto es para el editor visual estudio)
 ```
 ### utilizando editor nano (si queres esplayarte mas en el mensaje)
 1. lo inicias con git commit
 2. se abre el nano, escribis el mensaje del commit. 
 3. apretas Ctrl+O y despues apretas ENTER. Eso guarda el commit
 4. Apretas Ctrl+X y salis.

 ## RAMAS
 