POO
Sergio Ruiz

Apuntes de comandos básicos de Git utilizados durante el desarrollo del proyecto.

1. Clonar el proyecto
git clone url_proyecto .


Clona el repositorio remoto en la carpeta actual (.).

2. Configurar el usuario de GitHub
git config --global user.name usuario_github


Configura el nombre de usuario que Git utilizará para identificar los commits.

git config --global user.email email_github


Configura el correo electrónico asociado a los commits.

3. Verificar la configuración
git config --global --list


Muestra la configuración global de Git para comprobar que el nombre y el correo estén correctamente establecidos.

4. Agregar los cambios
git add .


Agrega todos los archivos modificados y nuevos al área de preparación (staging), dejándolos listos para realizar un commit.

5. Crear un commit
git commit -m "avance clase paciente"


Guarda los cambios preparados en el historial del proyecto. El texto entre comillas describe brevemente qué se modificó.

6. Subir los cambios al repositorio
git push origin main


Envía los commits de la rama main al repositorio remoto llamado origin.

Flujo básico de trabajo

En general, después de realizar cambios en el proyecto, podemos utilizar:

git add .
git commit -m "descripción de los cambios"
git push origin main


Este proceso permite agregar los cambios, guardarlos en el historial y subirlos al repositorio remoto.