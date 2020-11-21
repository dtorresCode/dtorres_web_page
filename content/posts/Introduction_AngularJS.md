---
title: 'Aprendiendo AngularJS'
date: 2020-11-21T15:16:58-06:00
draft: false
toc: false
images:
tags: 
  - AngularJS
  - Desarrollo
  
---

## Introducción

__AngularJS__ es un marco estructural para aplicaciones Web dinámicas el cual usa HTML como plantilla y permite extender la sintaxis de HTML para expresarlo en los componentes del mismo de forma clara y sencilla, ejecutándose todo  dentro del navegador, lo que simplifica el desarrollo de aplicaciones __CRUD__.

Esta inyección de dependencias ahorran gran parte de código al desarrollador.

AngularJS adopta un enfoque creando nuevas instrucciones dentro de HTML llamadas __directivas__ por ejemplo:

* Enlace de datos `{{}}`
* Estructuras de control DOM para repeticiones, mostrar y ocultar objetos, etc.
* Validación de formularios.
* Agrupación de HTML para componentes reutilizables.

AngularJS contiene lo siguiente listo para usar:

* Todo lo que necesitas para crear una aplicación CRUD en un conjunto cohesivo como enlace de datos, directivas básicas de plantillas, enlaces profundos, componentes reutilizables e inyección de dependencias.
* Historia de pruebas: Pruebas unitarias, pruebas de lado a lado.
* Aplicación inicial como punto de partida con diseño de directorio y scripts.

No todas las aplicaciones son adecuadas para AngularJS, el punto óptimo de AngularJS es simplificar aplicaciones de tipo __CRUD__, afortunadamente la mayoría de aplicaciones web representan este estilo, caso contrario son los editores de juegos y GUI que aunque utilizan la manipulación DOM de forma intensa y complicada no son adecuadas para AngularJS, para esos casos puede ser mejor utilizar una biblioteca con un nivel mas bajo de abstracción como `JQuery`.

El __Zen de AngularJS__ se basa en la creencia de que el código declarativo es mejor que  el imperativo cuando se trata de crear interfaces de usuario (HTML) y conectar componentes de software, mientras que el código imperativo es excelente para expresar la lógica de negocio.

Angular te libera y simplifica las siguientes actividades:

* __Registro de devolución de llamadas__: AngularJS elimina el código repetitivo común como las devoluciones de llamada lo que reduce enormemente la cantidad de codificación de JavaScript.
* __Manipular HTML DOM mediante programación__: AngularJS al escribir de forma declarativa como debería cambiar la interfaz de usuario a medida que cambia el estado de la aplicación, se libera de las tareas de manipulación de DOM de bajo nivel.
* __Escribir toneladas de codigo de inicializacion solo para comenzar__: Con AngularJS puede iniciar sus aplicaciones fácilmente inyectando dependencias que permitan desarrollar funciones rápidamente, como beneficio adicional se obtiene un control total sobre el proceso de inicialización en las pruebas automatizadas.

## Glosario:

* __DOM__: Document Object Model (Modelo de Objetos del Documento).
* __CRUD__: Acrónimo de Crear, Leer, Actualizar y Borrar.
* __GUI__: Graphical User Interface (Interfaz Gráfica de Usuario).


## Referencias:
[docs.angularjs.org/guide/introduction](https://docs.angularjs.org/guide/introduction)