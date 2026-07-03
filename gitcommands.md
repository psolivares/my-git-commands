Comandos de Git Hub principal

git init  "Se utiliza exclusivamente para crear un repositorio de Git completamente nuevo desde cero en tu computadora."
git branch -m rama "Cambia el nombre de la rama principal por "rama" "
git status "Me muestra el estado de mi git, como que no hay nada nuevo o actualizado"
git add . "Para añadir cada uno de esos ficheros" "El punto es para añadir todos los ficheros que estan pendientes"
git commit -m "crear un punto de guardado definitivo en el historial de tu proyecto, la -m es de mensaje". "Es el guardar como"
git checkout "Mover la aguja del tiempo de Git hacia un lugar específico, permitiéndote cambiar entre diferentes ramas o revisar cómo era tu proyecto en un commit del pasado"g


Empezar a subir fichero a Git
pablo@PO-PA-PC01:~/Hello Git$ git add . --Empezar a preparar, el contenido de la carpeta.
pablo@PO-PA-PC01:~/Hello Git$ git commit -m "Mi primer guardado" --Dale un nombre a este guardado para crear el historial en tu computadora:
pablo@PO-PA-PC01:~/Hello Git$ git push -u origin main 
**git push**: La orden para subir tus archivos al servidor.**-u:** Le dice a tu Git que recuerde esta configuración para el futuro.**origin:** Es el alias interno que apunta directamente a tu enlace https://github.com/psolivares/my-git-commands.git. Git ya sabe que ese es su destino.**main:** La rama de tu computadora que vas a enviar.