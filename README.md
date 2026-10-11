# WeePlay

## Autor/a

Sebastian Martin De Bosini Costa

## Descripción

WeePlay es una plataforma digital orientada al fútbol amateur que busca facilitar la organización y la práctica de este deporte.

La aplicación está pensada para conectar a jugadores que desean encontrar equipos y participar en partidos, equipos que necesitan gestionar sus jugadores y encuentros, y propietarios de canchas que quieren ofrecer reservas y organizar campeonatos.

Entre las funcionalidades previstas se encuentran el chat integrado, las estadísticas, los pagos digitales, las reseñas de establecimientos y las herramientas para conectar negocios patrocinadores con la comunidad deportiva.

El objetivo es centralizar la organización del fútbol amateur en un único lugar: menos tiempo buscando partidos y más tiempo jugando.

En esta primera entrega (EAC1) se prepara el entorno de desarrollo, la estructura inicial del proyecto Angular, las ramas de trabajo y la interfaz de presentación básica. Las funcionalidades completas de la plataforma se desarrollarán progresivamente durante el semestre.

## Versiones utilizadas

- Node.js: v24.18.0
- npm: 11.16.0
- Angular CLI: 22.2.2
- Angular: 22.2.2
- Git: 2.51.0.windows.2

## Cómo crear y ejecutar el proyecto

### Crear el proyecto Angular

El comando utilizado para crear el proyecto es:

```powershell
ng new ioc-angular-weeplay-sebastian-de-bosini-costa --routing --style=scss --ssr=false --standalone --file-name-style-guide=2016 --skip-git --package-manager=npm
```

Una vez creado, entrar en la carpeta del proyecto:

```powershell
cd ioc-angular-weeplay-sebastian-de-bosini-costa
```

### Instalar las dependencias

Para instalar las dependencias de un proyecto descargado o cuando sea necesario restaurarlas, ejecutar:

```powershell
npm install
```

### Ejecutar la aplicación

Desde la carpeta raíz del proyecto, ejecutar:

```powershell
ng serve -o
```

Angular iniciará el servidor de desarrollo y abrirá la aplicación en el navegador. Si no se abre automáticamente, acceder a:

http://localhost:4200/

Para detener el servidor de desarrollo, pulsar `Ctrl + C` en el terminal.

## Estado del EAC1

- Entorno de desarrollo verificado y configurado.
- Proyecto Angular creado con routing, estilos SCSS, arquitectura standalone y SSR desactivado.
- Estructura inicial preparada con las carpetas `components`, `services`, `models` y `pages`.
- Ramas de trabajo preparadas: `main`, `ra1-setup`, `ra2-components`, `ra3-serveis` y `ra4-navegacio`.
- Interfaz inicial personalizada con HTML, TypeScript y SCSS.
- Funcionamiento de la aplicación y actualización automática (_hot reload_) comprobados.

## Enlace del repositorio

Repositorio público de GitHub:

https://github.com/SebastianMartinDeBosiniCosta/ioc-angular-weeplay-sebastian-de-bosini-costa

Rama correspondiente al EAC1:

https://github.com/SebastianMartinDeBosiniCosta/ioc-angular-weeplay-sebastian-de-bosini-costa/tree/ra1-setup
