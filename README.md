# React.js-

## ¿Qué es React.js?

React.js es una biblioteca de JavaScript de código abierto utilizada para construir interfaces de usuario (UI). Desarrollada por Facebook, React.js se centra en la creación de componentes reutilizables y su principal característica es el uso de un enfoque declarativo para describir cómo debería verse una interfaz y cómo debería comportarse en función de los cambios de estado.

## Diferencias entre React.js versión 18:

### Routing:
React Router es una biblioteca popular utilizada para el enrutamiento en aplicaciones React. Las versiones posteriores de React pueden incluir mejoras o nuevas características en la gestión del enrutamiento.
Rendering: Se refiere al proceso de generar la interfaz de usuario en función del estado actual de la aplicación. Las versiones posteriores de React pueden incluir optimizaciones en el rendimiento de renderizado.
Data Fetching: React ofrece diversas formas de realizar la recuperación de datos, como el uso de hooks de efecto, fetch API, o librerías externas como Axios. Las nuevas versiones podrían incluir mejoras en este aspecto.
Styling: React no proporciona un mecanismo integrado para el estilo, pero es comúnmente utilizado junto con bibliotecas como styled-components o CSS modules. Las nuevas versiones podrían mejorar la integración con estas soluciones.
Optimizaciones: Cada nueva versión de React puede incluir mejoras en el rendimiento y optimizaciones internas para hacer que las aplicaciones sean más rápidas y eficientes.
TypeScript: React es compatible con TypeScript, lo que permite un desarrollo más seguro y escalable mediante la adición de tipos estáticos a JavaScript.
Conceptos detrás de React:

## Components:
### Los componentes
en React son bloques de construcción reutilizables para crear interfaces de usuario. Pueden ser piezas pequeñas como botones o entradas de texto, o componentes más grandes como menús desplegables o formularios completos.
### JSX: 
JSX es una extensión de sintaxis para JavaScript que permite escribir código similar a HTML dentro de JavaScript. Es utilizado en React para definir la estructura de los componentes de manera más intuitiva.
Props: Los props (abreviatura de "propiedades") son datos que se pasan de un componente padre a un componente hijo. Son inmutables y se utilizan para configurar un componente hijo.
State: El estado es un objeto que contiene datos relevantes para un componente. Es mutable y controlado internamente por el componente. Cuando el estado de un componente cambia, React se encarga de volver a renderizar el componente para reflejar esos cambios en la interfaz de usuario.

## Patrón de diseño Composite y su relación con React:

El patrón de diseño Composite se utiliza para componer objetos en estructuras de árbol para representar jerarquías de parte-todo. En React, este patrón se puede ver reflejado en la composición de componentes. Los componentes de React pueden contener otros componentes, lo que permite construir interfaces de usuario complejas combinando componentes más simples. Esto proporciona un alto nivel de reutilización y modularidad en el desarrollo de aplicaciones.

## Patrón de diseño State y su relación con React:

El patrón de diseño State se refiere a la gestión del estado dentro de una aplicación. En React, el estado es un concepto fundamental utilizado para almacenar datos que pueden cambiar durante el ciclo de vida de un componente. React proporciona una forma de gestionar el estado de manera eficiente a través del método setState() y los hooks de estado como useState(). Este patrón permite a los desarrolladores mantener un estado coherente y predecible en sus aplicaciones, lo que facilita el desarrollo y la depuración.
