# Illusion of life by Software

## Introducción

A través de este trabajo propongo la creación de un nuevo concepto relacionado a la animación y a la animatrónica, pero aplicado a programas informáticos.

Suele llamarse a la Animación el arte de la **ilusión de vida**, esto se debe a la capacidad que debe tener un artista de la animación para hacer que un elemento inanimado y estático, como puede ser un dibujo, o un muñeco parezca, frente al espectador, tener pensamientos propios, deseos y miedos.
No solo debe ese elemento estático cobrar movimiento, sino que debe ser capaz de generar empatía.

A su vez parecería que la creación de un agente de Inteligencia Artificial resultaría automáticamente en un agente que, si no tiene "vida", al menos genera una ilusión gracias a su comportamiento inteligente. Lamentablemente no es así, muchas técnicas tienen que ejecutarse en concordancia para dar lugar al surgimiento de **Ilusión de vida por Software** (a partir de ahora simplemente **ilusión**).

## Los N principios de la **ilusión**

A continuación detallo algunos principios que a mi entender deben seguirse para lograr la **ilusión**.
Los nombro *"Los N principios de la ilusión"* porque el número puede ir cambiando a lo largo del tiempo.

*Software*: Programa de computación, que generalmente tiene un fin concreto (informar, entretener, etc.).

*Usuario*: Ser humano interactuando con el software, generalmente con un fin concreto (obtener información, entretenerse, etc.).

*Estimulo*: La acción del usuario que está manipulando el Software (Click, Voz, Arrastrar, Texto, etc.).

*Respuesta*: La respuesta que brinda el Software al estímulo del usuario o del ambiente (Sonido, Texto, Animación, etc.).

> El software puede ser de procesamiento de lenguaje natural, de generación de imágenes y animaciones, o mixto.

### Ritmo (Timing)
La manipulación de los intervalos en los que suceden diferentes eventos genera un ritmo capaz de generar una respuesta emocional en el usuario.
- El tiempo de espera entre el estímulo y la respuesta
- La longitud de la respuesta
- El tipo de respuesta (texto, audio, imágenes, video)

### Gradientes y umbrales
Tiene que haber una relación entre el estímulo y la respuesta.

*Gradiente*: La intensidad de algunas respuestas será proporcional al estímulo.
Por ejemplo:
- **Estimulo**: Hoooolaaaaaa
- **Respuesta**: ¿Cooomooo estáaas?

*Umbral*: No habrá cierta respuesta, a menos que se cruce determinado umbral de intensidad en el estímulo.
- **Estimulo**: Hola
- **Respuesta**: ¡Hola!
- **Estimulo**: Hola
- **Respuesta**: ¡Buenas!
- **Estimulo**: Hola
- **Respuesta**: ¿Conoces otras palabras? (En este caso se cruzó el umbral de 2 repeticiones del mismo estímulo)

### Opinión
La respuesta debe decir algo acerca del estímulo del usuario.
Ejemplo tomado del libro *Create Convincing Computer Conversations*:
> Si un usuario responde a la pregunta "¿Cuál es tu color favorito?" diciendo "Rojo", responder "Amo ese color" es muy vago. [...] Sin embargo si el personaje responde "Oooh ¡Rojo! ¡Amo ese color!", es mas probable que el usuario se sienta comprendido.

### Fallback
Diseñar respuestas interesantes para estímulos inesperados (tomado del libro *Create Convincing Computer Conversations*).
Los personajes suelen definirse por la reacción ante situaciones límite, y la situación límite por excelencia para un software es cuando el usuario realiza una interacción para la cual no tiene una respuesta predefinida. *(buscar cita)*
Es interesante, también, que una de las definiciones de Inteligencia Artificial es "Un programa capaz de actuar cuando no sabe que acción tomar" *(Buscar cita)*

Los siguientes ejemplos muestran personalidades totalmente diferentes:
- **Estimulo**: ¿Cuánto es 2 + 2?
- **Respuesta Personaje 1**: Lo siento, no comprendo la pregunta
- **Respuesta Personaje 2**: ¡¿Qué?! Tengo mayores problemas aquí

### Puesta en escena (Staging)
La interacción debe ser clara, (Staging) el usuario debe saber que ha sucedido. Es uno de los doce principios de la animación.

### Atractivo
El software debe ser carismático, así sea un aliado o un villano.
Es, también, uno de los doce principios de la animación.

### Anticipación
Anticipar la respuesta del usuario, estar un paso por delante del usuario genera la ilusión de intuición en el personaje.

### Recompensa
El usuario debe ser recompensado al interactuar, debe sentir que toma decisiones de largo plazo en el desarrollo de la **ilusión**.

### Imperfecciones:
Los seres vivos tienden a cometer errores, una pequeña cantidad de imperfecciones puede ayudar con la ilusión.
- Si es un ser vivo orgánico: errores en la respuesta, duda, múltiples intentos, falta de reacción
- Si es un ser vivo inorgánico: interpretar de manera literal un estímulo, reaccionar exageradamente.

### Continuidad:
Debe parecer que la vida del personaje continua aún cuando el software no está corriendo, o cuando el usuario no interactuan con el.

## Análisis

A continuación analizo diferentes softwares para ver de qué manera utilizan estos elementos.

|Fundamento|Little Computer People|The Sims Mobile|Pou|Mitsuku|
|----------|----------------------|---------------|---|-------|
|Cadencia (Timing)|Regular en general, el perro agrega un ritmo mas irregular. Las acciones pequeñas tienen una cadencia mas rápida.|Acelerada, los movimientos son rápidos y las acciones concluyen prematuramente. Esto solo interrumpido por acciones que detienen la continuidad de la simulación|Suave y natural, con aceleraciones y desaceleraciones que respetan leyes físicas.|Responde instantáneamente, el largo de las respuestas se incrementa a medida de que la conversación avanza.|
|Gradientes y umbrales|Mayormente se maneja por umbrales, solo se puede apreciar un gradiente en el tanque de agua.|Mayormente se maneja con gradientes, hay umbrales que permiten acceder a nuevas acciones y objetos.|Mayormente se maneja con gradientes, hay umbrales que permiten acceder a nuevas acciones y objetos.|No maneja dradientes|
|Opinión|El personaje elige si realizar  la opción o no en base a su estado de ánimo. Y regularmente le escribe cartas al usuario expresando su opinión acerca de su desempeño.||El personaje reacciona a las interacciones del usuario, la mayoría de las veces de manera neutra, simplemente tornando los ojos hacia el punto de la interacción, pero otras veces de manera positiva (al hacer caricias) o negativa (al darle comida que no le gusta).|El personajes suele hacer comentarios acerca de las preguntas del usuario, por ejemplo si contienen faltas de ortografía.|
|Devolución (Feedback)|Al interactuar con comandos de texto algunas veces el personaje demuestra que está de acuerdo con el usuario haciendo el gesto de “si” con la cabeza. Al interactuar con atajos del teclado suele haber un sonido o animación como reacción.|Diferentes sonidos y animaciones dan a entender al usuario si la interacción fue exitosa o no.|Diferentes sonidos y animaciones dan a entender al usuario si la interacción fue exitosa o no.|El personaje responde inmediatamente, esa es su devolución.|
|Claridad|||||
|Atractivo|El personaje está continuamente actuando, aún cuando el usuario no realizó ninguna interacción.|Cada interacción resulta en una evolución en el personaje.|El personaje aparenta estar indefenso y requerir de nuestro cuidado.|El personaje siempre está disponible para escuchar lo que tengamos que decir.|
|Anticipación|El personaje recorriendo constantemente la casa sirve como anticipación (y demostración) de las posibles acciones que el usuario puede requerir.|Otros sims se acercan, se mantienen cerca o se alejan anticipando las acciones del usuario.|||
|Recompensa|El personaje escribe cartas de agradecimiento, y responde a las interacciones del usuario mas frecuentemente.|El usuario obtiene puntos que le permiten acceder a nuevas formas de interacción y objetos.|El usuario obtiene puntos que le permiten acceder a nuevas formas de interacción y objetos.||
|Imperfecciones|Cada copia del juego tiene un personaje diferente, al menos uno de los personajes escribe con errores.|No hay|No hay|El personaje puede malinterpretar algunos comentarios del usuario, con el fin de desviar el tema o dar una nota de humor.|
|Continuidad|Hay un personaje diferente para cada copia del juego, el estado del juego se guarda para continuarlo luego.|Al salir del programa y volver a entrar se muestra la evolución del personaje durante ese tiempo.|Al salir del programa y volver a entrar se muestra la evolución del personaje durante ese tiempo.|El personaje puede recordar aspectos del usuario e información de la conversación de una sesión a otra.|
|Aleatoriedad|El personaje realiza diferentes acciones por su cuenta, también puede elegir no ejecutar la acción requerida por el usuario.|La aleatoriedad está reducida al mínimo, solo presente en los sims que no el usuario no puede controlar.|El personaje puede rechazar cierto tipo de comida de vez en cuando.||

## Intersecciones
### Con la animación generada por ordenador
La animación generada por ordenador es la creación de personajes y ambientes a través de la manipulación de imágenes

### Con los videojuegos
Los videojuegos tienen varios puntos en común con el Animaware, es software, y muchos presentan personajes complejos, con los cuales podemos sentir empatía y que forman parte de una narración y un universo en el que podemos sumergirnos.
La diferencia radica …

Los videojuegos son una de las formas en que puede presentarse un Animaware, siempre y cuando se utilicen técnicas de programación para generar la ilusión de vida.

### Con los chatbots
Un Animaware puede presentarse en la forma de chatbot.

> Agregar cuadro con el espectro de posibilidades entre Animatronic y Animaware. Y Animación y Animaware.

# ANEXO I - Principios de la animación

- Estirar y encoger
- Anticipación
- Puesta en escena
- Animación directa y pose a pose
- Acción complementaria y Acción superpuesta
- Acelerar y desacelerar
- Arcos
- Acción secundaria
- Timing
- Exageración
- Dibujo Sólido
- Atractivo
