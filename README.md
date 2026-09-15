###### ***Jaime David Sanchez Hernandez***

###### ***Matrícula:***2630009

###### 

###### ***Nombre de la práctica:***Creación y sincronización de repositorios con Git y GitHub

###### 

###### ***Objetivo de la práctica:***Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos:

###### 

###### ***Descripción del procedimiento realizado:***

* Primero se creó una carpeta llamada ***practica\_git\_David\_Sanchez.*** Dentro de esta carpeta se abrió PowerShell y se inicializó un repositorio utilizando Git.
* Después se creó la rama principal con el nombre main y se agregaron los archivos **README.md** y **datos.txt**.
* Posteriormente, los archivos fueron agregados al área de preparación y se realizó el primer commit.
* Después se creó un repositorio público en GitHub y se vinculó con el repositorio local. Finalmente, se enviaron los archivos del repositorio local a GitHub.

###### 

|***Comandos de Git utilizados***|***Explicación breve de la función de cada comando***|
|-|-|
|git init|Inicializa un repositorio de Git.|
|git branch -M main|Cambia el nombre de la rama principal a main.|
|git status|Muestra el estado actual del repositorio.|
|git add .|Agrega los archivos al área de preparación.|
|git commit|Guarda los cambios en el historial del repositorio.|
|git remote add origin|Vincula el repositorio local con GitHub.|
|git remote -v|Muestra los repositorios remotos configurados.|
|git push|Envía los cambios del repositorio local a GitHub.|
|git pull|Descarga los cambios de GitHub al repositorio local.|



###### ***Explicación de cómo se creó el repositorio local:***

El repositorio local se creó desde PowerShell utilizando los siguientes comandos:



* mkdir ***practica\_git\_David\_Sanchez***
* cd ***practica\_git\_David\_Sanchez***
* git init
* git branch -M main



\-Después se crearon los archivos:

&#x20;   README.md

&#x20;   datos.txt



Se verificó el estado del repositorio y posteriormente se agregaron los archivos al área de preparación.

git status

git add .

git commit -m "Primer commit"



El comando git commit permitió guardar los primeros cambios en el historial del repositorio.



###### ***Explicación de cómo se vinculó el repositorio local con GitHub:***

Se creó un repositorio público en GitHub con el mismo nombre del repositorio local.



* Después se vinculó el repositorio local con GitHub mediante:

&#x20;     -git remote add origin URL\_DEL\_REPOSITORIO



* Para comprobar que la conexión se realizó correctamente se utilizó:

&#x20;     -git remote -v



* Finalmente, se enviaron los archivos a GitHub:

&#x20;     -git push -u origin main


###### ***Explicación de la sincronización Local → GitHub:***

* La primera sincronización se realizó enviando los archivos del repositorio local hacia GitHub mediante el comando:

&#x20;  -git push -u origin main

* De esta manera, los archivos ***README.md*** y ***datos.txt*** aparecieron en el repositorio de GitHub.



###### ***Explicación de la sincronización GitHub → Local:***

* Desde GitHub se modificó el archivo ***datos.txt*** y se agregó la siguiente línea:

&#x20;   -"Este archivo fue modificado desde GitHub."



* Después, desde PowerShell se descargó el cambio utilizando:

&#x20;   -git pull origin main



* Esto permitió actualizar el repositorio local con los cambios realizados directamente desde GitHub.



###### ***Descripción de los archivos contenidos en el repositorio:***

|**README.md**|Contiene la documentación de la práctica y los procedimientos realizados.|
|-|-|
|**datos.txt**|Contiene información inicial y los cambios realizados desde GitHub y el repositorio local.|



###### ***Conclusión personal sobre lo aprendido:***

Esta práctica me ayudó a entender mejor el funcionamiento del control de versiones y la importancia de Git para administrar proyectos.

