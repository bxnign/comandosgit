# comandosgit

------------------configuracones globales------------------

bajo que informacion se va a subir cada commit que hagamos

	git config --global user.name "nombre"  (configuramos el nombre)
	git config --global user.email-"email" (configuramos el email)
	
------------------comandos basicos para utilizar git------------------

iniciamos el repositorio local y le decimos a un proyecto que en us carpeta principal existira control de versiones	

	git init
	
agregamos todos los cambios que queremos subir al repositorio local

	git add .
	
generamos comentarios commit a las versiones que vayamos agregando al repositorio local
 
	git commit -m "comentario"
	
le indicamos a que repositorio queremos agregarlo

	git remote add origin "url del repositorio"
	
agregar todo al repositorio de github, podemos usar otro branch no necesariamente el por defecto (master)

	git push origin master

en caso de no haber iniciado sesion anteriormente se abrira una ventana para iniciar sesion en la cuenta de github

------------------cambiar y crear nuevos branch------------------

estos comandos funcionan bastante para el control de versiones,  puesto que cada branch tendra sus commit propio pero del mismo repositorio, asi se pueden hacer cambios sin afectar cambios anteriores de otros commit

	git branch (te lista los branch que exiten)
	git checkout (si pones uno que no existe te lo crea y te lo cambia, si indicas el que ya existe solo se cambia) 

------------------comandos varios------------------

	git status  ( te indica el estado de tus add)
	git clone "url" (te clona un repositorio ya creado en github para trabajar en el)

