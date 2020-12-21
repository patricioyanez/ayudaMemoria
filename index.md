## Comandos git para  subir proyecto

You can use the [editor on GitHub](https://github.com/patricioyanez/ayudaMemoria/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.


```markdown
Comandos para subir a github. Primero: Estar ubicado en la carpeta raiz del proyecto.

Comandos a ejecutar dentro de la carpeta anterior:

git init

git add .

git commit -m "Comentario"

git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

git push -u origin master
```




## Si aparece el siguiente error al ejecutar el comando:

git push -u origin master
```markdown
To https://github.com/patricioyanez/miRepo.git

 ! [rejected]        master -> master (non-fast-forward)
 
error: failed to push some refs to 'https://github.com/patricioyanez/miRepo.git'

hint: Updates were rejected because the tip of your current branch is behind

hint: its remote counterpart. Integrate the remote changes (e.g.

hint: 'git pull ...') before pushing again.

hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

# Ejecutar primero
git pull --rebase origin master

```markdown
From https://github.com/patricioyanez/miRepo

 * branch            master     -> FETCH_HEAD
 
Successfully rebased and updated refs/heads/master.
```



#_______________________
# Volver a versión anterior de un archivo del repositorio
#_______________________

```markdown
Para conocer las versiones de los ficheros según los commits, ejecutar:
git log
o
también puede ser
git log -n    (permite limitar los commits que se leeran). Ej:  git log -n 3 archivo.html
```


```markdown
Para restaurar un versión anterior, se utilza:
git checkout codigoDelCommit. Ejemplo:
git checkout b4a5ebef97b5ee5b543ebe046272f53695c37393

```
