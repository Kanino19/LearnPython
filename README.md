# LearnPython
Pasos para aprender python y git.

Pasos de instalacion del repositorio:\n

PASO 1 ! ----- Crear cuenta \n
(Imagen adjunta)\n
Crear cuenta en el siguiente link:\n
	https://github.com/\n
Conectarse a la cuenta (sing in).\n
Conectar a Setting (click sobre la imagen parte superior derecha).\n
Entrar a SSH and GPG keys (letras azules).\n
	https://github.com/settings/keys\n
Esperar al paso 3\n


PASO 2 ! ----- Instalar Git\n
Instalar git descargandolo del siguiente link\n
	https://gitforwindows.org/\n


PASO 3 ! ----- Configuracion clave SSH \n
Abrir CMD.\n
	Buscar en los programas con el nombre "CMD"(pantalla negra)\n
Crear la carpeta(escribir el texto despues del simbolo ">"):\n
	C:\Users\Joseph> mkdir .ssh\n
Entrar en la carpeta:\n
	C:\Users\Joseph> cd .ssh\n
Generar clave SSH:\n
	C:\Users\Joseph\.ssh> ssh-keygen -t rsa -b 4096 -C "email@gmail.com"\n

Genera dos archivos (id_rsa y id_rsa.pub) en la carpeta .ssh\n
Abrir id_rsa.pub con sublime o blog de notas\n
Copiar el contenido del archivo id_rsa.pub en setting/SSH key\n
	https://github.com/settings/keys\n


PASO 4 ! ----- Configuracion Git\n
Configurar git\n
\tC:\Users\Joseph> git config --global user.name "Joseph Kahn"\n
\tC:\Users\Joseph> git config --global user.email "email@gmail.com"\n

Uso de git\n

PASO 5 ! ----- Clonar el repositorio \n
Entrar al repositorio el cual se desea descargar.\n
	y 
	


