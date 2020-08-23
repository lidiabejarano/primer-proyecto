### Comentarios Generales

Lidia, lo primero es felicitarte por tu portfolio. Tu web quedó muy bien: adaptaste muy armoniosamente el diseño dado por Ada, respetando la consigna y a la vez dandole tu toque personal.

Quedó incumplida una parte de la consigna, que si bien es un detalle tengo que comentarte: uno de los requisitos era que los links del footer llevaran a las páginas externas correspondientes. Entiendo si no te sentís comoda compartiendo tus redes personales en un perfil de este tipo, pero habría sido preferible algún compromiso (llevar a facebook.com por ejemplo) en lugar de no agregar esos links, ya que uno de los objetivos de esta ejercitación es ver cómo aplican los conocimientos. 

En ese mismo sentido, tenés relativamente pocos commits hechos en git. Pedimos que se acostumbren desde ahora a trabajar con muchos commits ya que son muy importantes cuando trabajamos en equipo, y en el medio laboral. Cuando compartimos el código con otras personas, muchas veces podemos cometer algunos errores o tener que volver atrás un cambio en específico: ir haciendo commits seguido, e incluir nombres descriptivos en los commits, permite encontrar rápidamente el cambio que necesitamos, facilitando así la tarea. Lo ideal es ir trabajando por secciones: "agrego header", "agrego seccion principal", "agrego los estilos para celular", "corrijo estilos para tablet", etc. 

Con respecto al proyecto en github, si bien tu README cumple con los requisitos que pedimos, creo que vale la pena invertir en dejarlo un poco mas amable para el lector, especialmente si pensas usar este portfolio para presentarte en redes sociales o si estará en algun CV que eventualmente envíes. Te aseguro que mucha gente lee nuesto github cuando están evaluando contratarnos, y vale la pena darles la mejor experiencia posible. Por ejemplo: "Este es el primer trabajo práctico que hice en el marco del bootcamp de Front End de Ada ITW. Consiste en un portfolio personal, en el cual debíamos cumplir ciertos requisitos de estructura pero está estilado de acuerdo a mi preferencias. Las tecnologías usadas son HTML y CSS, incluyendo el uso de íconos de librerías externas como Font Awesome y DevIcons, flexbox como herramienta principal de maquetado y etiquetas semánticas.". 

Dejo algunos comentarios generales sobre tu código:

- Noto que repetis muchas veces font-family a lo largo de tu css. Recorda que el font-family se hereda
de padres a hijos, asi que lo mejor es darselo al elemento padre de todos (body) y luego cambiarlo
solo en aquellos elementos que usen un font family distinto, como tu nombre. Asi evitamos tanta repeticion. Imaginate si en algun momento queres modificar el font family de tu web: va a ser un enorme trabajo!

- Tu CSS esta algo desordenado: da la impresion de que lo hiciste, luego lo fuiste corrigiendo, pero no
acomodaste los nuevos estilos en el orden correcto. Por ejemplo, hay correcciones a container-skills dentro de la seccion de mis-proyectos, o estilos generales (a:link) dentro de algunas secciones. 
Es importante mantener el orden: estilos generales arriba de todo, cada seccion con sus estilos correspondientes en el orden en el que aparecen en tu HTML, y las media queries al final. 

- No usas las etiquetas semanticas salvo excepciones. Hay muchos <div> que deberian ser secciones
(por ejemplo, container-principal) y muchos div que deberian ser article (por ejemplo, principal). Tu footer tampoco tiene la etiqueta semantica correspondiente. Te deje anotado tambien algo sobre el uso de los h1, h2, etc.  

- Tengo que comentar y felicitarte por la prolijidad del código, tanto HTML como CSS. El orden, la estructura, el tabulado, el respeto por los espacios y buenas prácticas se nota a cada instante. Es un placer recorrer un código tan bien escrito para corregirlo, y no es habitual alcanzar esta prolijidad de escritura con tu experiencia. Felicitaciones por eso. 

- Tus media queries tienen el problema de excesiva repetición. Recordá que los estilos de los elementos se heredan a las media queries, asi que no es necesario repetirlos. Un elemento que tenga display: flex lo seguira teniendo en la media query. 

Dejo algunos comentarios específicos a lo largo de tu código. 

Obviamente mi trabajo es comentar todo lo que vea, asi que muchas veces puedo parecer muuuy quisquillosa en estos comentarios. Mi tarea es comentarte todo lo que vea para que puedas mejorar tu código: no habla de la calidad de tu trabajo, que es realmente muy bueno. 


### Nota final: 7

Nota desagregada: 
✅ Estructura correcta de documento HTML.
✔️ Respeta la consigna --> con observaciones
✅ Respeta el diseño dado --> con observaciones
✔️ Responsive funciona correctamente --> con observaciones 
✅ Código bien indentado. 
✅ Comentarios que permiten mejorar la legibilidad del código.
❌ Uso correcto de etiquetas semánticas.
✔️ Buenos nombres de clases ---> con observaciones
✔️ Reutilización de estilos --> con observaciones
✔️ Código CSS ordenado --> con observaciones
❌ Commits con mensajes adecuados.
