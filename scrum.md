# 📜 SCRUM Framework

Scrum es un framework para la gestión de proyectos complejos (Imagen A1), como el desarrollo de software. Scrum usa un conjunto prescrito de roles, reuniones y artefactos y divide una gran cantidad de trabajo en partes de una semana a un mes llamadas sprints. Se basa y emplea principios ágiles.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22304957/126039808-17abd952-bc25-48ca-86ab-9695c5f84f3f.png" style="width:20px;" />
  <p align="center"> Todos los derechos reservados a https://www.mitchlacey.com/</p>
</p>

Me gusta pensar en el equilibrio entre los roles, las reuniones y los artefactos que componen el sprint cycle como el de un auto de carreras finamente ajustado. Los pequeños ajustes incrementales pueden generar ganancias excepcionales. Al mismo tiempo, un golpe leve, un problema con el automóvil o su motor puede provocar una menor potencia, velocidades más lentas y un desgaste rápido del motor. ¿Cómo se relaciona esta analogía con Scrum? Las siguientes secciones exploran cada componente en detalle.

## 💼 Roles

Scrum consta de tres roles en cuanto a personas: el Scrum Master, el Product Owner y el Development Team (también nos referimos al Development Team como Team o Core Team). Juntos trabajan en los intereses de los clientes y las partes interesadas para convertir la visión que tienen en un producto o servicio funcional.

### 👮🏻‍♂️ ScrumMaster

Un auto tiene indicadores y sensores para ayudar a monitorear el motor y usa aceite para ayudar a lubricarlo. Sin aceite, el motor se detendría y se destruiría a sí mismo en el proceso. El aceite está en todas partes, manteniendo las partes del motor funcionando sin problemas, enfriándolas y asegurando que funcionan bien bajo estrés.

El ScrumMaster es así. Tiene sensores y medidores integrados que le permiten identificar cuando el equipo no se está desempeñando según su capacidad, y tiene las habilidades (lubricación) necesarias para ayudar a corregir los problemas. Ser ScrumMaster es un trabajo duro. Un buen ScrumMaster es alguien que nota las señales no verbales, se siente cómodo con los conflictos o problemas, es un comunicador eficaz, puede generar confianza, ganarse el respeto del equipo, y comprende la dinámica del mismo. Un buen ScrumMaster puede “evolucionar” el desarrollo. Puede generar confianza no solo en el equipo, sino también en los clientes y todos los interesados.

### 🏎 Product Owner

Si el ScrumMaster es el aceite y los sensores e indicadores del motor, el product owner es el conductor. El product owner apunta el automóvil en la dirección correcta y realiza los ajustes mínimos necesarios para **mantener el rumbo y obtener resultados**. Representa los intereses de los clientes y las partes interesadas. Su trabajo es establecer, nutrir y comunicar la visión del producto al equipo y a las otras partes interesadas, administrar el retorno de la inversión y las finanzas del proyecto, y tomar decisiones sobre cuándo crear un comunicado oficial (con la opinión de los clientes y las partes interesadas). El product owner es la única persona responsable en última instancia del éxito o fracaso del proyecto. Ella decide qué se desarrolla, cuándo se desarrolla y si lo que se ha desarrollado cumple con las expectativas esperadas.

### 👩🏻‍💻 Development Team

El equipo de desarrollo es como el motor del auto. Toda la conducción y la lubricación del mundo son inútiles sin un motor. El equipo de desarrollo ejecuta la visión del Product Owner con la ayuda del ScrumMaster. El equipo está compuesto por las personas necesarias para realizar el trabajo: `developers, testers, architects, designers, cualquiera que sea necesario`. Un equipo de desarrollo está formado idealmente por personas dedicadas a tiempo completo al proyecto. El equipo es responsable de administrar su trabajo, sus compromisos, y la ejecución de dichos compromisos. La mayor parte del material de Scrum dice que el tamaño ideal del equipo es de siete, más o menos dos personas. 

Prefiero números pares, ya que facilita una mejor integración de la práctica de ingeniería de XP (pair programming), por lo que mi regla sería seis, más o menos dos. El equipo es solo eso, un equipo: las funciones y los títulos deben eliminarse, lo que ayuda a construir la camaradería alrededor del equipo. El objetivo es eliminar la mentalidad de "Soy un desarrollador y solo escribo código" y cambiar la atención a "Soy un miembro del equipo responsable de realizar este trabajo y no puedo hacerlo solo". En un equipo de Scrum, los testers pueden escribir código y los desarrolladores pueden escribir tests; la funcionalidad cruzada es algo bueno no algo malo.

## The Artifacts

Scrum no es un proceso de desarrollo con muchos artefactos, pero tres artefactos son cruciales para el éxito: the product backlog, the sprint backlog y el burndown.

### The Product Backlog

El product backlog es la lista maestra, priorizada por **valor comercial y riesgo**, de todas las características y funcionalidades necesarias para implementar la visión y, al final, el producto o servicio en desarrollo para lograr esa visión. El product owner es responsable de administrar el product backlog, mantenerlo actualizado, priorizado u ordenado y claro. A diferencia de un documento de requisitos o una especificación de producto, el product backlog nunca está completo. En cambio, es un documento vivo que se expande o contrae en respuesta a cambios en prioridad, valor o riesgo. Los elementos se pueden agregar o eliminar del product backlog en cualquier momento. Una vez agregados, el product owner los prioriza en relación con los otros elementos: errores, características, mejoras, requisitos no funcionales, etc. La prioridad está determinada por el valor comercial y el riesgo, o cualquier pedido que tenga sentido para su empresa y proyecto. Los elementos de mayor prioridad están programados para desarrollar primero, mientras que los de menor prioridad se completan en último lugar (Imagen A2). El equipo trabaja con el product owner para estimar el tamaño de los elementos del product backlog (PBI), en relación entre sí. Ese tamaño se puede expresar en puntos, tallas de camiseta o cualquier otra unidad no específica de tiempo. La clave es mantenerse alejado de la estimación basada en el tiempo para los PBI.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22304957/126040242-879fb08c-f2f7-49a0-b504-7782d4a9fbed.png" />
  <p align="center"> Todos los derechos reservados a https://www.mitchlacey.com/</p>
</p>

Las historias de alta prioridad deben ser pequeñas y claras para que puedan incorporarse al sprint. Los elementos de menor prioridad pueden ser grandes y difusos. A medida que se completan los elementos de alta prioridad y los elementos de menor prioridad comienzan a ascender a la parte superior del backlog, las historias más grandes deben dividirse en partes más pequeñas, un proceso llamado descomposición de tareas.

### Sprint Backlog

El sprint backlog es el resultado de la reunión de planificación (planning meeting). Es esencialmente la lista de tareas que el equipo debe completar durante el sprint para convertir el conjunto seleccionado de tareas en un incremento de funcionalidad que se puede entregar. A diferencia de los PBI, las tareas pendientes de sprint tienen una estimación basada en el tiempo (por horas). Dado que el equipo está haciendo el trabajo, es responsable de mantener actualizado el backlog del sprint.

Durante un sprint, es posible que se descubran nuevas tareas y que se ajusten las que ya se han identificado. Este es un comportamiento perfectamente normal. El equipo simplemente agrega las nuevas tareas (y una estimación del trabajo restante en las tareas) al sprint backlog o ajusta la redacción (y, si es necesario, el trabajo estimado restante) para las tareas en progreso. A medida que el equipo completa las tareas, las tareas deben marcarse como realizadas en la lista de trabajos pendientes del Sprint. La lista de trabajos pendientes muestra a los miembros del equipo qué trabajo está completo y qué tareas quedan. Estos datos ayudan a los miembros del equipo a ejecutar un daily scrum efectivo (daily standup). Si bien se esperan cambios en el sprint backlog, el ScrumMaster debe estar atento a los patrones sobre el tipo o la cantidad de trabajo que se agrega o ajusta. Si surge un patrón, puede enseñarle a un equipo bastante sobre el sistema a medida que se construye y posiblemente sobre el equipo en sí.

### The Burndown

Si bien la Guía de Scrum publicada por Schwaber y Sutherland en octubre de 2013 dice que el burndown ya no es un artefacto requerido en Scrum, creo que sigue siendo una herramienta esencial en el arsenal de un equipo. Scrum requiere que los equipos comuniquen cuánto trabajo queda y qué tendencia tiene la finalización de tareas a lo largo del sprint. La mejor herramienta que he encontrado para realizar un seguimiento de este progreso es el sprint burndown, una imagen gráfica en tiempo real del trabajo que queda en el sprint. Se calcula graficando el número de horas restantes (eje y) contra el número de días restantes (eje x). Los graficos burndown se pueden escribir a mano o crear con una herramienta como Google Sheets u otra para esa tarea. Para actualizar la evolución del sprint, el ScrumMaster o el equipo traza el número de horas que quedan en el gráfico al final de cada día. Conectando esos puntos se muestra un gráfico del trabajo aún pendiente a medida que pasan los días del sprint. Puede visualizar si el equipo está en camino de completar todo el trabajo restante extrapolando la línea al último día del sprint.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22304957/126040838-87d6f8b5-c7ca-4304-afc4-7e990df88300.png" />
</p>

## Meetings

Scrum tiene cuatro reuniones: la planning meeting, el daily scrum (o standup diario), la sprint review y la team retrospective.

### Planning Meeting

Cada sprint comienza con una reunión de planificación de sprint de dos partes a la que asisten el equipo, ScrumMaster y el Product Owner. Para un sprint de un mes o cuatro semanas, esta reunión de dos partes debe durar ocho horas. Para un sprint de dos semanas, planifique unas cuatro horas. Como regla general, multiplique la cantidad de semanas en su sprint por dos horas para obtener la duración total de la reunión de planificación del sprint.

La primera parte de la reunión de planificación del sprint es una revisión de los posibles elementos del product backlog para el sprint. Este es el momento para que el product owner describa lo que quiere ver construido para el próximo sprint. Durante esta parte de la reunión, no es raro que el equipo bromee con el product owner, haciendo preguntas aclaratorias y alejando la ambigüedad. Al final de la primera parte de planificación del sprint, el equipo selecciona un objetivo del sprint, que debe ser una descripción de una oración del resultado general del sprint. Esto ayuda más adelante cuando surgen preguntas sobre la profundidad y la amplitud, ya que si el trabajo no se relaciona directamente con el objetivo del sprint, entonces no se realiza durante el sprint.

Durante la segunda parte de la reunión de planificación del sprint, el equipo decide cómo se construirá el trabajo. En esta reunión, el equipo comienza a descomponer los elementos del product backlog en tareas de trabajo y a estimar estas tareas en horas. El product owner debe estar disponible durante esta reunión, pero no tiene que estar en la sala. De hecho, a muchos equipos les resulta útil trabajar sin el product owner durante esta parte detallada de la reunión. Muchos equipos descubren que disfrutan discutiendo muchas posibilidades de implementación sin preocuparse de que el product owner entre en pánico o lo malinterprete. Si el propietario del producto permanece en la sala, el ScrumMaster debe hacerse cargo de esta parte de la reunión, manteniendo al equipo concentrado y libre para explorar posibilidades sin estar limitado por las propias ideas u opiniones del product owner.

### Daily Scrum

La reunión más frecuente que ocurre en Scrum es la reunión diaria, también conocida como daily scrum o daily standup. Independientemente de cómo se llame, el propósito sigue siendo el mismo: `darle al equipo la oportunidad de sincronizarse diariamente, a la misma hora y en el mismo lugar.`

El scrum diario es una reunión de planificación diaria en la que el equipo responde a un conjunto estándar de preguntas. Las tres preguntas más utilizadas son las siguientes:

1. ¿Qué ha logrado desde la última reunión?
2. ¿Qué lograrás hoy?
3. ¿Qué impedimentos u obstáculos se encuentran en su camino?

El scrum diario no es una reunión de resolución de problemas en profundidad; está destinado a identificar lo que hizo la gente, lo que hará y sus problemas, nada más.

Cualquier otro problema debe tomarse fuera de línea como elementos de acción para que el ScrumMaster lo resuelva o el equipo lo discuta más, según el problema. Al mismo tiempo, el daily scrum no es una reunión de informes de estado. Las personas deberían hablar entre sí, no informar de sus actividades al ScrumMaster. Su propósito es mantener a las personas enfocadas en lo que han hecho y harán. La única función del ScrumMaster es facilitar la reunión, no actuar como detective o capataz.

El equipo determina cuándo se llevará a cabo la reunión, pero debe ser todos los días a la misma hora y en el mismo lugar. El ScrumMaster y todos los miembros del equipo deben asistir todos los días. Se invita al product owner y a otras partes interesadas a asistir, pero es importante entender que esta reunión es para el equipo, no para ejecutivos, gerentes, líderes de desarrollo o cualquier otra persona. Si no asisten miembros del equipo, estarán en modo de "solo lectura" o "solo de escucha". No se les permite participar activamente, pero pueden mirar, escuchar y aprender.

Si se hacen bien, los daily scrums mejoran la comunicación del equipo, identifican problemas e impedimentos y crean un sentido de camaradería.

### Sprint Review

En el último día del sprint, el equipo realiza una revisión del sprint. Esta reunión (la duración, como la reunión de planificación del sprint, depende de la duración del sprint) brinda a los clientes la oportunidad de revisar el progreso realizado en el proyecto hasta la fecha y les proporciona un lugar para dar dirección u orientación al equipo con respecto al proyecto. El ScrumMaster, el equipo y el product owner deben asistir a la revisión del sprint. Además, el  product owner a menudo invita a los clientes, las partes interesadas y los ejecutivos a esta reunión. Durante la revisión, el equipo recapitula el objetivo del sprint y presenta el trabajo realizado. No es raro que los clientes elogien al equipo en esta reunión, ni tampoco es raro que los clientes soliciten cambios. Después de todo, la razón por la que los equipos hacen Scrum es para proporcionar ciclos de retroalimentación rápidos y múltiples oportunidades para inspeccionar y adaptarse; esta revisión es uno de esos bucles. Cualquier solicitud nueva debe incluirse en el product backlog y priorizarse. En esta reunión, el equipo debe solicitar la aceptación del cliente. A veces, los clientes dicen que algunas funciones no se entregaron o no se entregaron como se esperaba. En esos casos, el trabajo se puede volver a poner en el product backlog. Si se trata de un patrón recurrente, el  ScrumMaster debe anotarlo y abordarlo con el equipo.

### Sprint Retrospective

La retrospectiva del sprint sigue a la revisión del sprint. Brinda al equipo la oportunidad de identificar formas en las que puede mejorar su proceso de trabajo y la ejecución del framework de Scrum. La reunión es obligatoria para todos los miembros del equipo de Scrum. El ScrumMaster generalmente facilita la reunión, lo que ayuda al equipo a crear una lista de elementos de mejora priorizados que puede implementar en futuros sprints. Estos elementos deben revisarse en retrospectivas posteriores para que el equipo sepa cómo les está yendo y si se están produciendo mejoras. Una vez más, la duración depende de la duración del sprint. En esta reunión, el equipo debe responder (al menos) las siguientes dos preguntas:

1. ¿Qué salió bien durante este sprint?
2. ¿Qué se podría mejorar en el próximo sprint?

Todos deberían participar. El ScrumMaster no debería andar por la sala pidiendo respuestas a las personas. En cambio, el equipo debería escribir activamente sus respuestas en una pizarra. Una vez que los miembros del equipo hayan terminado de responder, deben trabajar juntos para priorizar los elementos y comenzar a decidir si se abordarán. Las retrospectivas que no tienen mucha actividad o que no generan cambios son frustrantes para todos los involucrados y, a menudo, llevan al equipo a cuestionar el valor de las retrospectivas. El valor proviene de las oportunidades de cambio identificadas en la retrospectiva. Si no se aprovechan las oportunidades y el equipo no mejora, hay un problema mayor.

## Conclusión

Las partes y las reglas por sí solas son fáciles de entender. Sin embargo, reunirlos de la manera más eficaz plantea desafíos. Volviendo a la analogía del auto, cada pieza debe estar finamente ajustada para un rendimiento óptimo. Luego hay que estudiar los detalles de implementación y las estrategias de la vida real para optimizar el rendimiento; moverse más rápido sin perder el control y lidiar con los golpes, las explosiones y los contraataques que surgen al intentar competir en el mundo del desarrollo de software.
