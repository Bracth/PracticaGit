# PracticaGit

Paso 11: Utilizo el comando git reset --hard HEAD~1 para retroceder un paso en mi repo y ademas diciendole a git que modifique mi working area al mismo tiempo.

paso 12: Utilice el comando git reflog y rastreando mis pasos anteriores busque el id del commit que elimine, luego utilize el comando git reset --hard con el id para 
moverme hacia el commit junto con la rama styled y modificando mi working area.

paso 13: No causa ningun conflicto porque la rama master ya se encuentra adentro de la rama styled.

paso 19: el merge causo un conflicto porque el archivo git-nuestro tiene diferentes cambios en las mismas lineas en cada rama.

paso 21: no me dio ningun conflico el merge porque los commit de master ya estaban adentro de la rama styled.

paso 25: Utilice el comando git log --graph para ver el diagrama.

paso 26: hice un merge fast forward sin querer, porque se me olvido agregar --n--f en el comando. se podia hacer fast foward porque no hay conflictos.

paso 27: Use el comando git reset HEAD-1 para deshacer el cambio sin alterar mi working copy

paso 28: Utilice el comando git restore git-nuestro para descartar los cambios.

paso 29: Con el comando git branch -D title elimine la rama.

paso 30: Tuve que buscar el id del commit gracias a reflog para hacer el merge nuevamente.

paso 32: Use el comando git reflog para ver el id del primer commit y luego el comando git checkout para ir hacia alli.

paso 33: Basicamente use el comando git checkout master para ir a la rama master en donde ya tiene el titulo del poema.

 
