# Guión practica 1(GIT)

## Comandos empregados:

```bash
git config 
> configurar os parametros de usuario de Git.
```     

```bash
git init        
> Inicialización do repositorio local.
```

```bash
git status        
> Comprobamos o estado do noso repositorio.
```

```bash
git add .       
> Añadir cambios ao repositorio,co modificador "." indicanos que queremos engadir todo.
``` 

```bash
git commit -m  
 > Engadir unha nova versión o noso repositorio,co modificador "-m" podemos   engadir un comentario.
``` 

```bash
git branch -M    
 > Cambiamos o nome da rama,co modificador "-M" indicamos que se trata da rama Main.
``` 

```bash
git remote add     
> Vinculamos o noso repositorio local co repositorio da nosa conta de  GitHub.
``` 

```bash
git push    
> Operacion definitiva para subir os cambios no repositorio online, a GitHub.
``` 

```bash
git clone + (link do repositorio)  
> Clonar o noso repositorio de GitHub nunha carpeta local.
``` 

```bash
git pull       
> Sincroniza o noso repositorio da conta online de Git co repositorio local,trae os cambios o noso repositorio local.
``` 

```bash
git log      
> Comprobar o estado do repositorio.
```
```bash
git --amend -m    
> Modifica a mensaxe do ultimo commit
```
```bash
git diff     
> Mostra a diferencia entre o commit anterior e o contido actual.
```
```bash
git show    
> Mostra a diferencia entre os dous ultimos commit.
```
```bash
git config --global color.ui auto  
> Da color as saidas por pantalla da consola de comandos.
```
```bash
git annotate    
> Mostra o historico de cambios dun ficheiro determinado.
```

```bash
git reset --hard HEAD~  
> Facer un reset completo tanto do commit coma do index coma do directorio de traballo indicandolle a que commit queremos volver.
```

```bash
git reset --mixed HEAD~  Facer un reset do commit e do index soamente sen afectar o directorio de traballo indicandolle a que commit queremos volver.
> 
```

```bash
git reset --soft HEAD~ 
> Facer un reset do commit  soamente indicandolle a que commit queremos volver.
```

```bash
git  clean -f
> borra os ficheiros que non estaban creados na ultima versión co modificador -f para forzar o borrado.
```

```bash
git  restore 
> utilizase para restaurar ,na rama de traballo ,o ou os aqrquivos especificados a un estado anterior especifico xeralmente o estado de rama actual.
```

```bash
git  checkout   
> equivalente a restore.
```

```bash
git branch (branch -av) con branch creamos unha rama e engadindo o modificador -av visualizamos as ramas.
> 
```

```bash
 git checkout xunto co nome da rama indicamos que queremos cambiarnos a unha rama en concreto.
> 
```

```bash
git  merge utilizase para levar o contido dunha rama a outra,pode ser dunha rama secundaría a rama MAIN ou viceversa.
> 
```

```bash
git commit (-a -m) forma abreviada de add + commit nun unico comando.
> 
```


## Pasos a seguir

1. Inicializamos o repositorio local co comando 'git init'
2. Creamos o noso contido no visual studio.
3. Gardamos as modificacions no repositorio con 'git add' e logo git commit
4. Creamos o repositorio no servidor online elexido,neste caso utilizamos GitHub.
5. Sincronizamos os cambios definitivamente co noso repositorio online utilizando 'git push'.