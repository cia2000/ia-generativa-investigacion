# Guion del bloque 2: conceptos básicos y demostración

**Duración estimada:** 6 minutos

Antes de entrar en la práctica, conviene aclarar cuatro ideas. No buscamos una definición técnica perfecta, sino un lenguaje común que nos ayude a usar estas herramientas con criterio.

La primera idea es que inteligencia artificial e IA generativa no son sinónimos. La inteligencia artificial es un campo muy amplio: incluye sistemas que reconocen una imagen, recomiendan una película, detectan un posible fraude o calculan una ruta. Algunos de estos sistemas llevan años presentes en herramientas que usamos a diario y no generan texto ni mantienen una conversación.

La IA generativa es una parte de ese campo. Se llama así porque puede crear contenido nuevo: texto, imágenes, código, tablas o resúmenes. Cuando escribimos una pregunta en un chat y recibimos una respuesta redactada, estamos usando IA generativa. Su capacidad para producir lenguaje natural hace que parezca que comprende exactamente lo que le pedimos. Pero debemos recordar que genera respuestas a partir de patrones aprendidos; no tiene criterio científico propio, no conoce nuestros objetivos si no se los explicamos y puede ofrecer información incorrecta de forma convincente.

Por ello, una respuesta de la IA debe tratarse como una propuesta de trabajo, nunca como una fuente definitiva. Puede ayudar a formular hipótesis, a preparar preguntas o a organizar información, pero las afirmaciones relevantes deben comprobarse en las fuentes originales y con el conocimiento experto del equipo investigador.

La segunda idea es la diferencia entre un chat y un agente. En un chat convencional escribimos una pregunta, recibimos una respuesta y continuamos la conversación. Normalmente la herramienta solo trabaja con lo que escribimos o con los documentos que adjuntamos de forma puntual.

Un agente es una herramienta de IA que puede trabajar dentro de un entorno de proyecto. Por ejemplo, puede leer los documentos que hemos puesto en una carpeta, proponer cambios en ellos, crear un borrador nuevo o ayudarnos a organizar materiales. Esto es útil porque el trabajo investigador rara vez cabe en una sola pregunta: suele estar repartido entre notas, preguntas, datos, referencias y versiones de documentos.

Esta capacidad no significa que el agente tenga libertad para decidir por nosotros. Al contrario: nos obliga a ser más claros. Debemos decidir qué carpeta abrimos, qué documentos puede consultar, qué tarea concreta queremos que haga y qué modificaciones estamos dispuestos a aceptar. La herramienta propone o ejecuta acciones, pero nosotros las revisamos y autorizamos. El control sigue siendo humano.

La tercera idea es que una buena conversación con la IA puede vivir en documentos, no solo en una ventana de chat. Un documento puede contener la pregunta que queremos investigar, el contexto del proyecto, las instrucciones de trabajo, las fuentes disponibles y los criterios con los que evaluaremos el resultado. De este modo, el contexto no depende solo de nuestra memoria ni desaparece cuando cerramos una conversación.

En esta sesión utilizaremos principalmente archivos Markdown. Markdown es un formato de texto sencillo. Permite escribir títulos, listas, enlaces y notas con unas pocas marcas fáciles de leer. Por ejemplo, un signo de almohadilla al inicio de una línea indica un título y un guion indica un elemento de una lista. Lo importante no es aprender toda su sintaxis hoy. Lo importante es que el archivo sigue siendo texto legible: podemos abrirlo, revisarlo, compartirlo y conservarlo junto con el resto del proyecto.

Trabajar con documentos Markdown tiene otra ventaja: mejora la trazabilidad. Podemos guardar qué instrucciones dimos a la IA, qué materiales le proporcionamos, qué borrador generó y qué correcciones hicimos después. Esto facilita retomar el trabajo, explicar cómo se llegó a un resultado y evitar que una conversación importante quede perdida en un historial de chat.

Vamos a ver ahora una demostración breve. Abriré una carpeta de proyecto que contiene documentos de ejemplo. Primero veremos qué archivos hay y leeremos uno de ellos para entender el contexto. Después plantearé una tarea limitada: organizar unas notas o proponer la estructura de un resumen. Observad tres aspectos: el contexto que recibe la herramienta, la precisión de la instrucción y la revisión que hacemos del resultado.

No buscamos que la IA resuelva una investigación en unos segundos. Buscamos aprender a dirigirla como una asistente: le damos un encargo concreto, comprobamos su propuesta y decidimos qué conservar, qué corregir y qué descartar.

## Speech sobre `AGENTS.md`

Hay un documento especial que veremos en esta carpeta: `AGENTS.md`. No contiene los resultados de la investigación ni una conversación con la IA. Su función es distinta: reúne las instrucciones estables del proyecto para orientar el trabajo de la herramienta.

En nuestro caso, indica para quién se prepara esta sesión, el tono que deben tener los materiales y algunos principios importantes, como proteger la confidencialidad, verificar las fuentes y mantener el criterio investigador. Cuando Codex trabaja dentro de esta carpeta, puede tener en cuenta esas pautas además de la petición concreta que le hagamos.

Podemos pensar en `AGENTS.md` como una breve guía de colaboración. Evita tener que repetir en cada petición las mismas normas de calidad y contexto. Sin embargo, no reemplaza nuestra instrucción: seguiremos indicando qué documento queremos analizar, qué resultado esperamos y cómo vamos a revisarlo.

También podemos crear instrucciones más específicas en subcarpetas cuando un proyecto lo necesite. Lo importante es que estas instrucciones sean claras, breves y revisables. De este modo, los documentos del proyecto conservan tanto el contenido del trabajo como las reglas con las que queremos que la IA nos ayude.
