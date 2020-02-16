11- Utilicé el comando **git reset --hard HEAD~1** porque se solicita perder los cambios realizados en el Working Copy
12- Utilicé primero el comando **git reflog** para identificar el commit al que queria volver. Despues utilicé el comando **git reset --hard 714ae46** con el identificador
13- No causo ningun conflicto, porque simplemente se mueve el puntero MASTER y HEAD de la rama absorvida; la informacion de styled no pierde nada con respecto a master.
19- Si causo conflicto, porque la foto del mismo archivo del repositorio de la rama absorvedora (styled) es diferente a la del mismo archivo de la rama absorvida (htmlify). 
21- No causo conflicto, porque anteriormente habiamos mergeado styled (absorvedora) con master (absorvida).
25- Primero defini un alias para **git config alias.grafico "log --graph --decorate --pretty=oneline"** para dar comodidad al trabajo, y despues lo ejecute con **git grafico*
26- El merge no podria ser fast forward, porque existe el mismo archivo modificado con el titulo en la rama absorvida.
27- Utilicé el comando **git reset HEAD~1**, porque deshace el ultimo commit/merge sin perder el contenido de la Working Copy
28- Utilicé el comando **git checkout -- git-nuestro.md**, para descartar los cambios. En el caso de que la pregunta se refiera a abortar el merge seria **git merge --abort**
29- Utilicé el comando **git branch -D tittle**. La forcé porque daba conflicto al no estar mergeada del todo
30- Utilicé **git reflog** para localizar el HSA del merge, y despues utilicé **git reset 1861a1b**
32- Utilicé **git reflog** para localizar el HSA del merge, y despues utilicé **git checkout 4c3d63a**
33- Utilicé **git reflog** para localizar el HSA del merge, y despues utilicé **git checkout 53fc6c3**