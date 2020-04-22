# meh-3
mi primer repositorio
git 
Comandos:
>cd desktop
>cd <nombreProyecto> -> (proyecto la cual creé)
>git init -> inicializar proyecto a traves de git -- luego de presionar enter automaticamente se crea un archivo '.git' --
>git status  -> es para saber que archivos tenemos y/o con los que estamos trabajando
depende del color de los archivos del proyecto:
* rojo: aun no estan incluidos en staying area (entorno de trabajo)
* verde: esta agregado al entorno de trabajo que conforma la version de tu programa.
> git add <file>  -> es para agregar el archivo de proyecto hacia el staying area
>git add . -> sirve para agregar todos los archivos
> git commit -> es  para realizar los cambios (te va a pedir verificacion del usuario que hace configuraciones pidiendote un email o tu nombre)
git commit -m "comentario" 
git log -> muestra las ultimas modificaciones y comentarios si esque se han hecho
git branch ->  Muestra las ramas existentes.
git branch <nombreRama>  -> crear una rama nueva
git checkout <nombreRama> -> elegir rama
Guardar/deshacer cambios
**realizar cambios en el archivo (escribir codigo en editor de proyecto 'atom')**
> git status  --> te indicara que existen cambios no guardados
> git checkout -- <file>  -> volver a la ultima actualizacion guardada (del commit)
>git diff <file> ->  si se realizan cambios en el edito de proyecto, el comando te mostrara las diferencias de lo que estaba antes y lo que se agregò:
*Rojo: el antes, lo que se quito.
*Verde: texto que se agrego.
entonces para guardar los cambios que se hicieron se debe hacer lo siguiente: 
git add <file>  (se agregara al area de trabajo)
git status (te mostrara el estado del archivo como modificado)
git commit -m "comentario"
Solo carpetas seleccionadas
**Si quiero agregar carpetas indicando cuales quiero ignorar se hara lo siguiente**
->se creara un archivo llamado "test"
->pero si quiero ignorar el archivo "test" se creara una carpeta llamada  ".gitignore" la cual                             
    escribiras como texto el nombre del archivo ("test")
->verificar en git status que se vea la carpeta ".gitignore" y no el archivo "test"
-> guardar en el commit con comentario.
