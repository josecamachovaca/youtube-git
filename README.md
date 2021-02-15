# Comandos utiles de Git

1. git init			inicializa el repositorio
2. git add .			agrega los archivos desde el ultimo commit.  sube los archivos al stage
3. git reset .			revierte lo k hace el git add .  baja los archivos del stage
4. git commit			guarda todo lo del stage
5. git checkout -- .		revierte los cambios desde el ultimo commit
6. git log			muestra el historial de los logs
7. git commit --amend		permite modificar el ultimo commit, su comentario
8. git checkout -b rama-heroes	crea una nueva rama llamada rama-heroes
9. git branch			lista las ramas
10. git checkout master		se cambia a la rama master
11. git merge rama-heroes	hace un merge desde la rama heroes hacia la rama actual
				presionar ESC wq!  para salir y que se grabe el merge inmediatamente
12. git branch -d rama-heroes	borra la rama rama-heroes
13. git push			sube todos los cambios al repo
14. git commit -am "coment"	es como hacer un git add . y un git commit al mismo tiempo
