# Documentación de la Práctica de Git

---

## 1. ¿Qué es Git?
Git es una plataforma que nos permite tener un control exhaustivo de versiones en un repositorio en la nube.

---

## 2. ¿Cuál es el flujo de trabajo de Git?
El flujo se organiza mediante los siguientes entornos de trabajo:

Directorio local
: Es la carpeta en la que trabajamos en nuestro ordenador y donde se realizarán todos los cambios.

Repositorio local
: Contiene los cambios que se realizan en el directorio local que decidimos subir a Git.

Repositorio remoto
: Contiene todos los cambios que se han realizado y subido al servidor.

---

## 3. Comandos realizados durante la práctica

A continuación se detallan las acciones realizadas mediante comandos de consola:

- **git add**
  : Prepara los archivos modificados del directorio de trabajo para el próximo commit.
- **git commit**
  : Subir los cambios del directorio local al repositorio local.
- **git push**
  : Subir los cambios del repositorio local al repositorio remoto.
- **git pull**
  : Descargar todos los cambios del repositorio remoto a nuestro directorio local.
- **git fetch**
  : Descarga el historial del servidor remoto sin modificar tus archivos locales actuales.
- **git merge**
  : Une dos ramas de desarrollo distintas dentro del repositorio.

---

## 4. ¿Qué es un conflicto de Git, qué lo causa y cómo podemos solucionarlo?

### Causa del conflicto
A veces, al hacer **push**, nos encontraremos el problema de que el archivo que hemos editado nosotros también lo ha modificado otra persona.

### Opciones de solución
Ante este conflicto podemos decidir de forma manual una de las siguientes soluciones:
- [ ] Quedarnos con nuestros cambios (`HEAD`)
- [ ] Quedarnos con los cambios del repositorio (`MASTER`)
- [ ] Quedarnos con los cambios de los dos

---

## Capturas de pantalla de la práctica
![Descripción de la imagen](/Images/picture.jpg)
