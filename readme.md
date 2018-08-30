en este documento se intenta generar un ejercicio de push y pull.

Primeros pasos CON ARCHIVOS YA CREADOS:
1. Si la carpeta ya esta generada en la computadora local, ir a la carpeta de interes y solo ejecutar --->  git init
2. si tiene archivos, ejecutar el siguiente comando para generar el repositorio remoto ---> 
git remote add origin https://github.com/serch86/prueba_git.git  (esto es para indicarle que el repositorio local sera el que llenara el 
repositorio remoto)
3. posteriormente es necesario agregar los archivos al repositorio remoto con los siguientes comandos:
git add .    (el punto se refiere a que agregue todo lo que encuentre en la carpeta o puedes hacer con git add -A que son analogos) 
_indexado_
git commit -m "Mensaje relevante a la modificacion o agregacion del codigo"       (se genera el commit) _head_
git push -u origin master  (se genera el push para subir el codigo al repositorio remoto __nube__ ) _envio de cambios_

