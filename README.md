# Pruebas-Git-

git init (Volver a conectarnos con el proyecto de git remoto)

git branch (Muestra las branch del repositorio)

git branch Osvaldo (Crear una nueva branch)

git checkout Osvaldo (Cambiarme a una branch 'Osvaldo' el nombre de la branch a cambiarnos)

git pull (Descargar ultimos cambios de alguna branch ) 
Tú21:09
git pull origin 'chile' 'Ricardo' 'Osvaldo'  (nombre segun la branch a actualizar)

git merge 'Osvaldo' 'Ricardo' ( Clonar os cambios de la rama mas actualizada a la personal, (marcara errores si no hemos hecho commit de nuestra rama) y validar si hay errores en el merge) 

Posterior a hacer el merge, subir nuestros cambios 

git add . (recolectar los cambios de nuestros archivos y prepararlos para subirlos a git remotamente)

git commit -m "como identificare el commit" 
(-m indica que puedo hacer comentarios multilinea)
Tú21:10
git push origin 'Rama en la que vamos a mandar el commit'