A continuación respondo a las preguntas solicitadas en el punto 4:

### 1. ¿Porque no debería usar la libreria JQuery, si estoy usando ReactJS?
jQuery es una librería de Javascript que nació con la intención de unificar la forma de manipular el DOM con Javascript que fuera compatible con todos los navegadores de la época, dado que cada uno implementaba su propio estándar. ReactJS es una librería de UI para construcción de aplicaciones web, utiliza Javascript y Babel para transpilar código a Javascript compatible con todos los navegadores.

### 2. ¿Porque usarias Hooks de las nuevas versiones de ReactJS, en lugar de class component?
Los componentes funcionales tienen mejor performance que los componentes de clase en Javascript, además de que en Javascript no existen las clases como propiemente están definidas en la POO. Otra ventaja es que el manejo del ciclo de vida se hace mucho más simple y menos suceptible de efectos no deseados, puesto que en el componente de clase, la misma instancia de la clase persiste durante todo el ciclo de vida del componenten, mientras que en componentes funcionales, por cada re renderizado del componente es una nueva ejecución de la función.

### 3. ¿Qué es un archivo JSX?
Es un archivo Javascript que contiene sintaxis JSX para el template de un componente de React.

### 4. ¿Que diferencia hay entre una function y una arrow function de Javascript?
Una diferencia importante es que una arrow function siempre es una función expresada y no declarada. Además, las arrow functions heredan el contexto en donde son ejecutadas, por lo tanto no crean un nuevo contexto para la palabra reservada this.

### 5. ¿Que es Redux y cómo nos ayuda en los proyectos?
Es una librería que permite mantener un estado global de la aplicación en Javascript. Es una implementación del patrón flux, muy cercano a la forma de trabajo de React, pero sin ser exclusivo para aplicaciones en React.

### 6. ¿Que nos permite hacer la siguiente declaración?
```const anyFunction = (param_1) => (param_2) => param_1 + param_2```

Esa función se conoce como closure, y nos permite utilizar funcionalidad del contexto de la función interna en un contexto fuera de ella.
