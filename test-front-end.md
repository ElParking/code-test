# Prueba de código para Frontend
La prueba de código consiste en crear una aplicación web sencilla solo front-end, cero back-end. [Aqui puedes ver con una propuesta de diseño](https://github.com/ElParking/code-test/blob/master/font-end/sample-designs.md).

## Funcionamiento
La idea es hacer un trivial de números. Para ello se usará la API de [Numbers API](http://numbersapi.com/).

El funcionamiento es el siguiente:
- Se deben responder a 10 preguntas y cada pregunta será sobre un número, escogido al azar.
- En cada pregunta se presentarán las opciones posibles y el usuario tendrá 30 segundos para responder.
- Se irá guardando el progreso hasta contestar a las 10 preguntas. El usuario podrá ver las preguntas que ya ha respondido de alguna forma.
- Al terminar el juego se presentará una página resumen con los resultados obtenidos y una opción para volver a jugar.

## Objetivos principales
- Estructurar correctamente el estado de la aplicación y las transiciones de la misma.
- Diferenciar claramente las responsabilidades para cada componente.
- Controlar los diferentes casos de error que se puedan plantear (errores en la API, etc.)
- Testing: Todos las capas deberían tener al menos un test (unitario, integracion). No hace falta cobertura 100%.

### Extras
- Añadir una barra de progreso para el tiempo restante de cada pregunta que, segun va avanzando, cambie de color.
- Implementar un diseño responsive.
- Persistir el estado del juego, de modo que al recargar la página todo continue donde se quedó.
- Utilizar Redux para gestionar el estado de la aplicación.
- Se valorará el uso de hooks
- Se valorará el uso de [styled-components](https://styled-components.com/)

## Tecnologías
- Usa React 16 o superior como framework JS. 
- Organizar el código como si fuera el inicio de algo más grande.
- Valoraremos el uso de la nueva sintaxis ES6
- Puedes usar [react-create-app](https://facebook.github.io/create-react-app/) para el bootstrap de la aplicación.
- Para los tests te recomendamos usar [jest](https://jestjs.io/).
- Sube el código desde el inicio a un repositorio de Github/Bitbucket/GitLab para que luego podamos ver los commits y la evolución.
- La aplicación tendrá que estar accesible para que podamos probarla. Para ello te recomendamos usar un servicio como [netlify](https://www.netlify.com/) o [now](https://zeit.co/now) (no es necesario que sean estos).

## Notas
- Esto es una prueba de código y se tratará como tal. No hace falta que quede perfecto, pero sí que funcione :D.
- Es una prueba que si se realiza completa requerirá dedicarle bastante tiempo. Se valorará si se realiza completa, pero no es indispensable. Lo que queremos ver es el estilo de código y la manera de resolver los problemas. 
