# prueba-git
Experimentando cómo utilizar Git desde consola

## Puedes descargar Git desde su sitio web oficial:
https://git-scm.com/

## En mi caso, me fue de utilidad este video introductorio en español:
https://youtu.be/HiXLkL42tMU

---
16:37 git init

### Iniciar un repositorio en la carpeta actual donde estemos en la consola.
	git init


---
17:41 git status

### Ver qué archivos están dentro del "arbol de trabajo" (archivos añadidos para actualizarce el siguinte commit)
	git status


---
18:19 git add

### Añadir un archivo al arbol de trabajo.
	git add archivo.txt

#### Añadir todos los archivos modificados al arbol de trabajo.
	git add .

---
20:01 git commit

### Hacer un commit en la rama actual.
	git commit -m "Mensaje de descripcion del commit"


---
20:37 git config

### Establecer tu nombre de usuario y tu correo en el repositorio local.
	git config --global user.mail "ejemplo@gmail.com"
	git config --global user.name "Nombre Apellido"
	
Nota: Puedes usar git config --list, o mirar tu archivo ~/.gitconfig. La configuración local estará en el archivo .git/config de su repositorio.
	(Esto lo visualizaras dentro del programa de consola Less, para salir de el, precionas la tecla 'q')


---
23:02 git log

### Ver historial de commits en el repositorio.
	git log


---
24:55 git checkout -- <name file>

### Restaurar un archivo a un punto anterior
	git checkout -- archivo.txt

---
25:45 git diff

### Ver cambios en un archivo modificado.
	git diff 

---
29:39 .gitignore

Puedes crear un archivo con el nombre .gitignore en el repositorio.  Dentro puedes colocar nombre de archivos o carpetas que no quieras que se tomen en 
cuenta para el repositorio. 
Es una buena forma de, por ejemplo, no tener en cuenta los archivos binarios compilados en el repositorio.


---
32:16 git commit -m <message>

### Hacer un commit en la rama actual, mandando un mensaje de descripcion directamente como parametro.
	git commit -m "Esto es un commit"

---
33:35 git branch <branch name>

### Crear una nueva rama.
	git branch nueva-rama

---
33:58 git checkout <branch name>

### Moverse entre ramas.
	git checkout nueva-rama
---
35:17 agregar archivos de una vez con git add .


---
41:15 crear un repositorio en github
43:33 git remote

### Establecer el "origen" en linea (el enlace del repositorio en Github, por ejemplo) del repositorio que se esta trabajando.
	git remote add origin https://github.com/...


---
44:10 git push

### Subir cambios en una rama al repositorio en linea.
	git push -u origin "nombre-de-la-rama"


---
48:30 git clone

### Descargar una copia de un repositorio remoto (en linea) en la carpeta actual.
	git clone https://github.com/...
