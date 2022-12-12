# Comando útiles de Git

1. git init

2. git add .

borra lo ultimo que se agrego en el add
3. git reset .

guarda los cambios con un mensaje
4. git commit -m "mensaje con el que se guarda el commit"

regresa al ultimo commit
5. git checkout -- .

muestra los commit en el historial
6. git log

permite editar el mensaje del ultimo commit
7. git commit --amend

## ramas
crear una rama llamada rama-heroes
7. git checkout -b rama-heroes

cambiar a la rama master
8. git checkout master

''' unir ramas '''
9. git merge rama-heroes

ver las ramas 
10. git branch

borrar las ramas
11. git branch -d rama-heroes
