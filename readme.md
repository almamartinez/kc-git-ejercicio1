#Ejercicio 1

###**¿Qué comando utilizaste en el paso 11?**
	
		git reset --hard HEAD~1

* **¿Por qué?** Porque había que deshacer el último commit perdiendo los cambios del working copy.

###**¿Qué comando o comandos utilizaste en el paso 12?**
	    
	    git reflog
	    git reset --hard 8c3cacb

* **¿Por qué?** Primero listamos el log del repositorio para localizar el commit al que queremos volver, y utilizamos el identificador para volver a él con la segunda instrucción. 

###**El merge del paso 13, ¿Causó algún conflicto?** **¿Por qué?** 
**No causa conflictos**. La información de **master** ya está contenida en **styled**. 

###**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
**Sí**, porque en ambas ramas hay un commit del mismo fichero modificado en las mismas líneas y *git* no sabe cómo resolverlo.

###**El merge del paso 21, ¿Causó algún conflicto?** **¿Por qué?**
**No**, porque fue un *merge fast-forward*. El merge fue linear.

###**¿Qué comando o comandos utilizaste en el paso 25?**
	log --graph --decorate --pretty=oneline
	

###**El merge del paso 26, ¿Podría ser fast forward?****¿Por qué?**
**Sí**, porque los cambios entre ambas ramas son lineares, forman una lista.

###**¿Qué comando o comandos utilizaste en el paso 27?**

	git reset HEAD~1
	

###**¿Qué comando o comandos utilizaste en el paso 28?**

	git checkout -- git-nuestro.md

###**¿Qué comando o comandos utilizaste en el paso 29?**

	git branch -d title
	git branch -D title

###**¿Qué comando o comandos utilizaste en el paso 30?**

	git reflog
	git reset --hard 2f0fcfe

###**¿Qué comando o comandos usaste en el paso 32?**
	git branch -d htmlify
	git branch -d styled

###**¿Qué comando o comandos usaste en el punto 33?**
	git log
	git reset --hard ed096dd92d42447970846ed6985bc6be5be16e11