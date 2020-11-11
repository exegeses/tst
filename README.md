#Branching

> crear nueva branch huérfana

    git checkout --orphan <branchname>   

    git checkout --orphan catalogo   

> limpiar caché y directorio 

    git rm --cached -r .    

> ya podemos hacer un nuevo commit 

    git commit -m 'nueva branch creada' --allow-empty   
    git push origin catalogo   

