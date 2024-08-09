# NestJS-spanish-guide

<br>

<br>

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

<br>

<br>

<hr>

## Introducción a NestJS

### ¿Qué es NestJS?

NestJS es un framework que se utiliza para la construcción de aplicaciones del lado del servidor en Node.js y está construido con TypeScript.


### Características principales

- **Estructura modular:**
    
    Facilita la organización del código en módulos reutilizables. Esto mejora la mantenibilidad y la escalabilidad de las aplicaciones.

- **Soporte para TypeScript:** 

    Aunque también es compatible con JavaScript, NestJS está diseñado con TypeScript en mente.

- **Arquitectura inspirada en Angular:** 

    Si estás familiarizado con Angular, notarás que NestJS comparte algunos conceptos clave, como los módulos, controladores y servicios. Esto facilita la curva de aprendizaje para desarrolladores que ya conocen Angular.

- **Compatibilidad con múltiples paradigmas:** 

    NestJS permite trabajar con diferentes paradigmas de programación, como la Programación Orientada a Objetos, Funcional y Reactiva, lo que ofrece flexibilidad en la forma en que se desarrollan las aplicaciones.

- **Integración fácil con otras bibliotecas:** 

    Gracias a su naturaleza modular, es fácil integrar NestJS con otras bibliotecas y frameworks de Node.js, lo que te permite aprovechar un ecosistema amplio y maduro.

<br>

<br>

<hr>

## Instalación de NestJS

### Requisitos Previos

1. NodeJS

2. NPM o Yarn

    NPM viene preinstalado con Node.js

    En cambio Yarn se tiene que instalar: https://yarnpkg.com/

<br>

### Instalación del CLI de NestJS

NestJS proporciona un CLI (Command Line Interface) que facilita la creación de nuevos proyectos y la generación de componentes como controladores, servicios, módulos, etc.

**Usando NPM**

```sh
npm install -g @nestjs/cli
```

**Usando YARN**

```sh
yarn global add @nestjs/cli
```

**Verificar instalación**

```sh
nest --version
```

<br>

<br>

<hr>

## Creación de un Nuevo Proyecto

```sh
nest new nombre-proyecto
```

### Ejecutar la app

Al generar el nuevo proyecto, tendremos varios ficheros creados.

Nos guiamos según lo que ponga en el fichero **package.json** en la sección de **scripts**.

Siempre que queramos ejecutar alguno de esos scripts lo haremos con ```npm run <nombre del script>```, en mi caso estoy usando linux, lo haré de la siguiente forma:

```bash
npm run start:dev:linux
```

<br>

<br>

<hr>

## Estructura del Proyecto

NestJS organiza el código en módulos, controladores y servicios:

- **Módulos:** 
    
    Agrupan código relacionado (por ejemplo, controladores y servicios) y son la unidad básica de organización en NestJS.
    
Controladores: Se encargan de manejar las solicitudes HTTP y devolver respuestas al cliente.
    
Servicios: Contienen la lógica empresarial de la aplicación y son utilizados por los controladores.
