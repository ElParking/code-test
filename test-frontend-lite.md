# Prueba de acceso

![PARKLE](https://github.com/ElParking/code-test/blob/8c09ef46ac721d13058997606f27cf37089dd24a/font-end/626a17d232805.png)

La prueba de código consiste en crear una aplicación web sencilla solo front-end, cero back-end.

## Funcionamiento
La idea es hacer la "Pregunta del día". Para ello se usará la API de [opentdb](https://opentdb.com/).

El funcionamiento es el siguiente:
- La App consistira en 2 pantallas una pantalla de bienvenida y otra con un formulario.
- Se deben responder a 1 pregunta, escogida aleatoriamente de las que devuelva la API.
- Se presentarán las opciones posibles.
- Se mostrará si el usuario ha acertado o no.

Puedes añadir funcionalidad adicional si lo consideras oportuno.

## Objetivos principales
- Estructurar correctamente el estado de la aplicación, las rutas y las transiciones de la misma.
- Diferenciar claramente las responsabilidades para cada componente.
- Controlar los diferentes casos de error que se puedan plantear (errores en la API, etc.)
- Testing: Todos las capas deberían tener al menos un test de los siguientes tipo (no hace falta cobertura 100%):
   - Unitario -> con [JEST](https://jestjs.io/) o similar
   - Interacción -> con [CYPRESS](https://www.cypress.io/) o similar

### Extras
- Mostar un timer de 30 segundos y que determine si ha fallado el usuario.
- Permitir que el usuario solo juegue una vez al día. Guardar datos en cache del nevegador.
- Se valorará el uso de hooks.
- Se valorará el uso de [styled-components](https://styled-components.com/)

## Tecnologías
- Usa React 16 o superior como framework JS. 
- Organizar el código como si fuera el inicio de algo más grande.
- Puedes usar [react-create-app](https://facebook.github.io/create-react-app/) para el bootstrap de la aplicación.
- Sube el código desde el inicio a un repositorio de Github/Bitbucket/GitLab para que luego podamos ver los commits y la evolución.
- La aplicación tendrá que estar accesible para que podamos probarla. Para ello te recomendamos usar un servicio como [netlify](https://www.netlify.com/) o [now](https://zeit.co/now) (no es necesario que sean estos).

## Notas
- Esto es una prueba de código y se tratará como tal. No hace falta que quede perfecto, pero sí que funcione :D.
- Es una prueba que si se realiza completa requerirá dedicarle bastante tiempo. Se valorará si se realiza completa, pero no es indispensable. Lo que queremos ver es el estilo de código y la manera de resolver los problemas. 
