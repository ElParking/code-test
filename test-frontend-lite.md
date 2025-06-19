# Prueba de acceso

![PARKLE](https://github.com/ElParking/code-test/blob/master/font-end/626a17d232805.png)

La prueba de código consiste en crear una aplicación web sencilla solo front-end, cero back-end.

## Funcionamiento
La idea es hacer la "[Palabra del día](https://lapalabradeldia.com/)". Para ello se usará una API que nos ofrezca una palabra random. Un ejemplo puede ser: [random-word-api](https://random-word-api.herokuapp.com/home).

El funcionamiento es el siguiente:
- La App consistira en 2 pantallas una pantalla de bienvenida y otra con el juego.
- En la pantalla de bienvenida se seleccionará el idioma de la palabra y la longitud.
- En la pantalla del juego se replicará el juego del [Wordle](https://lapalabradeldia.com/).
   - Será un formulario con una caja de texto en el que se irán poniendo palabras hasta lograr adivinar la palabra del día.
   - Tenemos que dar feedback al usuario de que letras hemos acertado y cuales no.
   - Se dará 5 oportunidades de acertar.
   - Se mostrará si el usuario ha acertado o no.

Puedes añadir funcionalidad adicional si lo consideras oportuno.

## Objetivos principales
- Estructurar correctamente el estado de la aplicación, las rutas y las transiciones de la misma.
- Diferenciar claramente las responsabilidades para cada componente.
- Controlar los diferentes casos de error que se puedan plantear (errores en la API, etc.)
- Testing: Sería necesario hacer algun test de cada capa de la aplicación usando Jest y React Testing Library. No hace falta el 100% coverage. 
### Extras
- Buena UI/UX y responsive
- Mostar un timer de 120 segundos y que determine si ha fallado el usuario.
- Permitir que el usuario solo juegue una vez al día.
- Se valorará el uso de hooks.
- Se valorará el uso de [styled-components](https://styled-components.com/)
- Se valorará que la aplicación sea accesible. Se pueden usar herramientas para apoyarnos con esto. Un ejemplo son [Lighthose](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=es) o [Axe DEv Tools](https://chromewebstore.google.com/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd?hl=es-419)

## Tecnologías
- Usa React 16 o superior como framework JS. 
- Organizar el código como si fuera el inicio de algo más grande.
- Puedes usar [react-create-app](https://facebook.github.io/create-react-app/) para el bootstrap de la aplicación.
- Sube el código desde el inicio a un repositorio de Github/Bitbucket/GitLab para que luego podamos ver los commits y la evolución.
- La aplicación tendrá que estar accesible para que podamos probarla. Para ello te recomendamos usar un servicio como [netlify](https://www.netlify.com/) o [now](https://zeit.co/now) (no es necesario que sean estos).

## Notas
- Esto es una prueba de código y se tratará como tal. No hace falta que quede perfecto, pero sí que funcione :D.
- Es una prueba que si se realiza completa requerirá dedicarle bastante tiempo. Se valorará si se realiza completa, pero no es indispensable. Lo que queremos ver es el estilo de código y la manera de resolver los problemas. 
