Por qué odio los IDEs
=====================

Empecemos quitando de la discusión algunas cosas importantes:

* Usar un IDE y tomar ventaja de lo que tiene que ofrecer no significa que sea
  un mal programador, y usar un buen editor de texto no significa que sea bueno.
* Usar un IDE puede **convertirlo** en un mal programador.
* Depender de un IDE significa que es un mal programador.

Pienso que muchas personas estarán de acuerdo sobre esto, así que continuemos.

Continuaré actualizando esta lista en el futuro, si tiene algo que le gustaría
agregar aquí por favor déjeme saber.


Entonces cual es el problema con los IDEs?
------------------------------------------

* Una capa adicional de problemas y errores
    * El servidor de pruebas no funciona? Probablemente es culpa del IDE, no el
      código.
    * El código no compila? Bueno, su código esta bien, el IDE no sabe una
      mierda sobre las librerías, o quizas alguna configuración es requerida.

* No estropees mis ficheros!

* No te metas con mi sistema de control de versiones!

* Varias operaciones básicas y comunes requieren un click con el mouse.

* La documentación para la interfaz de librerías se vuelve opcional si el IDE
  tiene un botón para hacerlo.
  * Cuando quiero usar una librería quiero documentación!, no me digas
    simplemente que debo "hace click ahí y funcionará automáticamente".

* Deja de desperdiciar mis pixeles!
    * El código! Quiero que el código sea lo principal en pantalla, no un
      diminuto espacio en el centro.

* (Los IDEs son posibilitadores de malos lenguajes de
  programación)[https://dzone.com/articles/ide-bad-programming-language]

* Editor! Por favor! Un buen editor!!! Trabajo con texto!
  * No me obligas a usar el mouse.
  * Revisión de sintaxis, auto completado, etc. Todas esas cosas están bien,
    pero el editor sigue siendo la parte más importante.

* No uses el mouse!
  * El código es texto, quiero mantener mis manos sobre el teclado.
  * Programar ya es una tarea mentalmente agotadora, por qué hacerlo una tarea
    físicamente agotadora tambien?
  * Mover la mano desde el teclado hasta el mouse miles de veces para alcanzar
    algun estupido botón de una GUI o para lograr alguna edición de texto por
    que el editor del IDE apesta es simplemente estupido.

* Devuélveme mis recursos!
  Quiero toda es memoria y CPU para la compilación, no para la edición del
  código!

* Debe ser programable o morir, si no se tiene algo que deseamos que tenga, o si
  tiene una idea que le permitiría mejorar su flujo de trabajo debería ser capaz
  de simplemente implementarlo! (Emacs, Vim, Sublime y Atom son buenos
  ejemplos).

* Combinar pequeños, y especializadas herramientas siguiendo la filosofía UNIX,
  no poner todo en una gigante y horrible pila de basura.

* Como es posible que una librería funcione correctamente desde un IDE pero no
  desde otro? Ya es lo bastante estúpido y malo que sea dependiente del
  compilador en algunos casos, pero dependiente del IDE? Tienes que estarme
  jodiendo!
  [Cita requerida: Esto me ocurrió a mi una vez con alguna librería gráfica para
  C, lo describiré aquí en cuanto lo recuerde y pueda recrear el problema]

* Puedes por favor dejar de lanzar ventanas emergentes y señales hacia mi todo
  el tiempo para que pueda ver el código?

* Rápido, simple y automático es una cosa; Tratar al programador como un
  retrasado es otra.

* Déjame compilar sin el IDE!
  * Algunos IDEs Tienden a ser codiciosos y compilar fuera del IDE se vuelve
    casi imposible.

* Si le toma más de 1 segundo en arrancar, es estúpido.

* Una herramienta para todos los trabajos.
  No usas un IDE para los ficheros de configuración del sistema,
  ficheros de configuración de demonios, scripts de la shell ni nada de esa
  naturaleza verdad? Entonces... Dominar un buen editor de texto es un
  requerimiento.

* Si el IDE sabe más que tu, eres un idiota!. A los programadores no les gusta
  la magia.

* La Automatización es buena!, pero si **tienes** que usar un IDE para
  implementar un servicio web en una aplicación JSF por que no hay otra forma en
  la que no tenga que atravesar por un proceso traumático, entonces está
  enterrado en mierda.

* Si no puedes hacer algo sin un IDE, el lenguaje apesta, tu apestas, o ambos.



Por supuesto que no todo IDE tiene todos estos problemas al mismo tiempo sino
solamente un subconjunto de ellos. Todo se puede solucionar, un buen IDE si es
posible.
