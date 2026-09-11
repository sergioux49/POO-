# Programación Orientada a Objetos (POO)
**Autor:** Sergio Ruiz

Guía rápida de comandos básicos de Git para el control de versiones de un proyecto.

---

## 1. Clonar un repositorio existente
```bash
git clone url_proyecto .
```
**Explicación:** Copia (descarga) un repositorio remoto desde una URL a tu máquina local. El punto (`.`) al final indica que el contenido se descargará directamente en la carpeta actual, sin crear una subcarpeta adicional.

---

## 2. Configurar el nombre de usuario global
```bash
git config --global user.name usuario_github
```
**Explicación:** Establece el nombre de usuario asociado a los commits que realices en tu sistema. La bandera `--global` aplica esta configuración para todos los repositorios en tu equipo.

---

## 3. Configurar el correo electrónico global
```bash
git config --global user.email email_github
```
**Explicación:** Configura la dirección de correo vinculada a tu cuenta de GitHub/Git. Debe coincidir con el correo registrado en GitHub para que tus contribuciones se reconozcan correctamente.

---

## 4. Listar las configuraciones globales
```bash
git config --global --list
```
**Explicación:** Muestra la lista de todos los parámetros globales configurados en Git (como tu nombre, correo, editor por defecto, etc.) para verificar que los datos ingresados sean correctos.

---

## 5. Añadir cambios al área de preparación (Staging Area)
```bash
git add .
```
**Explicación:** Prepara todos los archivos modificados, creados o eliminados en el directorio actual para ser incluidos en el siguiente commit. El punto (`.`) abarca todos los cambios.

---

## 6. Registrar los cambios en el historial (Commit)
```bash
git commit -m "avance clase paciente"
```
**Explicación:** Guarda una instantánea (*snapshot*) de los cambios previamente añadidos al área de preparación. El parámetro `-m` permite incluir un mensaje descriptivo que explica de qué trata la actualización (en este caso, avances en la clase `Paciente`).

---

## 7. Subir los cambios al repositorio remoto
```bash
git push origin main
```
**Explicación:** Envía los commits guardados en tu rama local (`main`) al servidor remoto (`origin`, que usualmente es GitHub), actualizando el proyecto en la nube.
git commit -m "descripción de los cambios"
git push origin main


Este proceso permite agregar los cambios, guardarlos en el historial y subirlos al repositorio remoto.
