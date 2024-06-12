<p align="center"><a href="#" target="_blank"><img src="https://duragaspromo.com/img/logo.png" width="400" alt="Duragas Logo"></a></p>

# Proyecto Familia Duragas

## 1.- Requisitos

- Se requeriere conectarse a la VPN para acceder a los servicios o aplicativo de Duragas

- Tener instalados las siguientes herramientas: [Manual de instalacion de herramientas](https://github.com/JoelBaj/API/blob/main/Herramientas.md)

## 2.- Contenido

- [Clonar Repositorio](#3--guia-de-cómo-clonar-el-repositorio-del-proyecto)
- [Guia de proyectos del Backend](https://github.com/JoelBaj/API/blob/main/backend.md)
- [Guia de proyectos del Frontend](https://github.com/JoelBaj/API/blob/main/frontend.md)

## 3.- Guia de cómo clonar el repositorio del proyecto

<!-- 3.1.- Primero debe copiar la url del respositorio -->

3.1.- Abrir la terminal git bash, dirigirse al directorio en donde desea clonar el repositorio.

3.2.- Escriba `git clone` y adjuntar la dirección URL del respositorio.

```bash
git clone [URL DEL REPOSITORIO]
```

## 4.- Proceso de creación y cambios de rama del repositorio

- Al clonar el repositorio, por defecto estará en la rama master
- En caso de realizar modificaciones en la API, consultar al dueño del repositorio antes de subir los cambios, en el cual le indicará si se debe crear una nueva rama o si los cambios deben aplicarse a una rama existente.

  ### 4.1- Crear una nueva rama

  - Para crear una nueva rama, escribir el siguiente comando:

  ```bash
    git checkout -b nueva-rama
  ```

  ### 4.2- cambiar de rama

  - Para moverse a la rama de "nombre-de-la-rama", para ello debe escribir el siguiente comando.

  ```bash
  git checkout nombre-de-la-rama
  ```

  ### 4.3- Subir cambios al git

  - Para subir los cambios al repositorio, escibir los siguientes comandos:

  ```bash
  git status
  git add .
  git commit -m "mensaje-del-commit"
  git push -u origin 'nombre-rama'
  ```

## 5.- Sección Backend - Frontend

Una vez hecho todo los pasos anteriores, dirigirse a la guia del backend y frontend para realizar las respectivas configuraciones. [Volver a contenido](#2--contenido)

<!-- ## 6.-Documentacion de Git

- [Git](https://git-scm.com/docs/git/es)
- [GitHub](https://docs.github.com/es/repositories/creating-and-managing-repositories/cloning-a-repository) -->
