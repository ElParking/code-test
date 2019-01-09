Prueba de código para Frontend
==================================
La prueba de código consiste en crear una web-app sencilla con solo front-end, cero back-end. [Aqui puedes descargar un PSD (y un zip con las imágenes sueltas)](https://www.dropbox.com/sh/2wj7yzp7xm091t5/AACwtdj67tH3Fm2CnDnRmEOva?dl=0) con una propuesta de diseño para la web-app.

Funcionalidades
=================
Lo que queremos hacer es un Trivial de números. Para eso vamos a usar la API de [Numbers API](http://numbersapi.com/).

El funcionamiento básico debe ser el siguiente:
- Se deben responder a 10 preguntas y cada pregunta será sobre un número, escogido al azar
- En cada pregunta se presentarán las opciones posibles y el usuario tendrá 30 segundos para responder.
- Se irá guardando el progreso hasta contestar a las 10 preguntas. El usuario podrá ver las preguntas que ya ha respondido de alguna forma. 
- Al final, se presentará una página de resumen con el resultado del "trivial".
- Controlar los diferentes casos de error que se pueden dar. 
- Testing: Todos las capas deberían tener al menos un test. No hace falta cobertura 100%.

"Bonus Points" de funcionalidad
-----------------
- En la página de cada pregunta habrá una barra de progreso en cada pregunta que, segun va pasando el tiempo, irá cambiando de color. 
- La página debe ser responsive.
- Usando solo javascript, que se guarde el estado del trivial y, si cierro la página y la vuelvo a abrir, que siga por donde me había quedado. 
- Proponer un diseño diferente al aportado teniendo en cuenta que debe ser responsive. 

Tecnologías
==============
- CSS: Usar algun tipo de preprocesador de CSS y organizar el código css como si esto fuera el inicio de un proyecto más grande.
- Javascript: Lo ideal es usar React+Redux como framework base (es en lo que trabajamos en ElParking). Al igual que con el CSS, pensar en esto como si fuera el inicio de algo más grande. 
- Javascript: recomendable seguir el nuevo estandard de Javascript ES6
- Uso de "module bundler": En ElParking usamos Webpack, pero se puede usar cualquiera. 
- Sube el código desde el inicio a un repositorio de Github/Bitbucket para que luego podamos ver los commits y la evolución.

Notas
=======
- Esto es una "prueba de código" y se tratará como tal. Es decir, se valorará el código, no hace falta que funcione todo correctamente. Eso si, si funciona, pues mucho mejor :D. 
- Es una prueba que si se realiza completa requerirá dedicarle bastante tiempo. Se valorará si se realiza completa, pero no es indispensable. Lo que queremos ver es el estilo de código y la manera de resolver los problemas. 
