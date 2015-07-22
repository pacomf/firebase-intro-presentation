# Introducción a Firebase en Español

Estas diapositivas pueden ser personalizadas para dar una charla introductoria a Firebase. La presentación está
hecha con [reveal.js](http://lab.hakim.se/reveal-js), un fantástico e increíble framework para crear presentaciones HTML.

### [Ver la Presentación](https://crackling-fire-6272.firebaseapp.com/)

## Setup

Este repositorio usa npm y Grunt para instalar las dependencias necesarias, construir la presentación, ejecutar los tests y lanzar el contenido en un servidor web local. Para empezar, ejecuta los siguientes comandos:

```bash
$ git clone git@github.com:firebase/firebase-intro-presentation.git
$ cd firebase-intro-presentation         # para acceder al directorio de firebase-intro
$ npm install -g grunt-cli               # para instalar grunt task runner
$ npm install                            # para instalar las dependencias
$ bower install                          # para instalar la dependencia de polymer
```

Para crear la presentación y ejecutar los tests:

```bash
$ grunt
```

Para ejecutar la presentación usando un servidor web local:

```bash
$ grunt serve
```

## Despliegue

Lo ideal sería desplegar la presentación en un sitio web público para que cualquier persona la pudiera ver. Puedes usar el [Hosting de Firebase](https://www.firebase.com/docs/hosting/) para desplegar la presentación de forma grauita.

Sino, puedes ver la presentación en local accediendo a [http://localhost:8000](http://localhost:8000).
