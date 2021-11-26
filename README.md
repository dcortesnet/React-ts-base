# Template de desarrollo React frontend ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

> React

> Typescript

> Nginx

> Docker

> CI/CD

Descripción del proyecto : Proyecto template de directrices para la estandarización de un proyecto, el objetivo del proyecto es que los desarrolladores puedan seguir la estructura conformada por este proyecto tanto como su archivo README, estructuras de carpeta estándar y su ciclo básico de CI/CD, con el motivo de mejorar y facilitar los tiempos de desarrollo y despliegue en cada uno de los proyectos.

## Tabla de contenido

- [Comenzando](#comenzando)
    - [Prerrequisitos](#prerrequisitos)
    - [Instalación](#instalación)
    - [Docker](#docker)
    - [Desarrollo](#desarrollo)
- [Pruebas](#pruebas)
    - [Test](#test)
- [Compilación](#compilación)
- [Equipo](#equipo)

## Comenzando

A continuación se listarán todos los puntos necesarios para comenzar a desarrollar con el proyecto actual desde su fase de instalación hasta levantar un ambiente local de desarrollo sin problemas, se incluirán instrucciones de ejecución de comandos, testing, reglas y contexto de como esta estructurado el proyecto incluyendo su estructura de carpetas junto con su descripción.

## Prerrequisitos

1. Node js
    * https://nodejs.org/es/download/
2. Docker
    * https://docs.docker.com/get-docker/
3. Yarn
    * https://classic.yarnpkg.com/en/docs/install/#windows-stable

* **Recuerda configurar tus llaves ssh**
    * https://docs.gitlab.com/ee/ssh/
    * https://docs.github.com/es/free-pro-team@latest/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

## Instalación

```bash
$ yarn install
```

## Docker

```bash
$ docker build -t example .
$ docker run -d -p 80:80 example
```

## Desarrollo

Ejecutar `yarn start` para un servidor de desarrollo. Navega a `http://localhost:3000/`. La aplicación se recargará automáticamente si cambias cualquiera de los archivos fuente si estas en el modo watch.

```bash
$ yarn start
```
## Pruebas

Las pruebas son necesarias para la construcción de nuevas funcionalidades dentro del proyecto, estas pruebas están ligadas a un ciclo de vida de CI/CD que se ejecutará al subir un nuevo cambio en las ramas, se aconseja ejecutar pruebas unitarias o de integración antes de subir una nueva funcionalidad al repositorio, esto es importante para evitar posibles errores en el futuro.

## Test

Ejecuta `yarn run test` para ejecutar las pruebas de todo el proyecto.

```bash
$ yarn run test
```

## Compilación

Ejecuta `yarn run build` para construir el proyecto. Los artefactos de la construcción serán almacenados en el directorio `build/`.

```bash
$ yarn run build
```
## Equipo

Desarrollado por Diego Cortés

* dcortes.net@gmail.com
