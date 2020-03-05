# Comandos en git.
- Cambiar a una rama del repositorio remoto: 

  `git checkout --track origin/develop`


- Añadir todos los cambios y hacer el commit: 

  `git add .` `git commit -m "comentario"`
  
- Crear una etiqueta

  `git tag` `git push --follow-tags`
  
  `git tag` `git push --tags`
   
- Añadir cambios al ultimo commit

  `git add .` `git commit --amend -m "comentario"`
  
- Hacer un push forzando los cambios

  `git push origin master --force-with-lease`

- Deshacer un commit

  `git revert [idCommit]`
  
- Deshacer un add

  `git rm`
