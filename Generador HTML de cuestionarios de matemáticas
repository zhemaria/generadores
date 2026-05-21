# Generador HTML de cuestionarios de matemáticas

**Una herramienta para profesores de matemáticas del programa GED en español, que crea cuestionarios interactivos con feedback inteligente, listos para publicar en la web.**

Forma parte del ecosistema [GEDparaHispanos.com](https://gedparahispanos.com), un proyecto educativo abierto y gratuito dedicado a apoyar a los adultos hispanohablantes que estudian para el examen de equivalencia de secundaria (GED) en los Estados Unidos.

---

## ¿Qué hace este generador?

Es una página web autocontenida (un solo archivo HTML) que les permite crear cuestionarios interactivos de matemáticas en minutos, sin necesidad de conocimientos de programación. Ustedes solo escriben el tema, configuran el tipo y nivel de las preguntas, y reciben:

- Un archivo HTML descargable, listo para subir a GitHub Pages, Google Sites, Brightspace, Moodle, o cualquier otro sitio web.
- Cuestionarios completamente responsivos, accesibles y autocontenidos (no requieren base de datos ni servidor).
- **Feedback inteligente por opción**: la IA explica el error específico que produce cada distractor, no genera respuestas genéricas tipo "esto es incorrecto".
- Diseño limpio basado en principios de Diseño Universal para el Aprendizaje (DUA), con tipografía Atkinson Hyperlegible (mejora la lectura para personas con dislexia).

## Lo que hace especial al feedback

Cuando un estudiante elige una respuesta incorrecta, no recibe un simple "te equivocaste". Recibe una explicación del error de razonamiento que pudo llevarlo a esa respuesta concreta. Por ejemplo, si la pregunta dice *"Juan compra 3 manzanas a $2.50 y paga con $10, ¿cuánto cambio recibe?"* y el estudiante elige $7.50, el feedback dice:

> *Calculaste el total de la compra (3 × 2.50) pero olvidaste restarlo del billete de $10.*

Este tipo de retroalimentación específica convierte cada error en una oportunidad de aprendizaje real.

## Tipos de pregunta disponibles

- **Opción múltiple**: 4 opciones, una correcta, feedback específico para cada distractor.
- **Respuesta múltiple**: varias respuestas correctas en una misma pregunta.
- **Verdadero / Falso**: con explicación tanto si el estudiante acierta como si falla.
- **Respuesta corta numérica**: el estudiante escribe la respuesta y se compara con tolerancia (acepta comas o puntos decimales).

## ¿Qué necesitan para usarlo?

Solo tres cosas:

1. **El archivo HTML del generador**, que ustedes mismos pueden descargar de este repositorio.
2. **Una clave de API de Groq** (gratuita y rápida de obtener — explicado más abajo).
3. **Un navegador web moderno** (Chrome, Firefox, Edge, Safari).

No hace falta instalar nada ni saber programar. Se ejecuta enteramente en su navegador.

## Cómo obtener su clave de API de Groq (gratis)

Groq es un servicio que les permite usar el modelo de IA Llama 3.3 70B sin costo, con una clave personal. Cada profesor debe obtener su propia clave (toma menos de un minuto):

1. Visiten [console.groq.com/keys](https://console.groq.com/keys).
2. Regístrense con su correo o con cuenta de Google (no piden tarjeta de crédito).
3. Hagan clic en **"Create API Key"** y copien la clave (empieza con `gsk_...`).
4. En el generador, hagan clic en **⚙️ Configurar API**, peguen la clave y guarden.

La clave se almacena únicamente en su navegador (localStorage). No se envía a ningún servidor más que al de Groq cuando ustedes generan preguntas. Nadie más puede verla.

## Flujo de trabajo típico

1. **Configuren el cuestionario**: tipo de pregunta, cantidad (hasta 10), área matemática, nivel de dificultad, enfoque (problemas de palabras, cálculo directo, conceptual, o análisis de datos), y un título.
2. **Escriban el tema** en el chat del generador (por ejemplo: "ecuaciones lineales", "porcentajes con descuentos", "perímetro y área combinados"). Pueden también cargar PDFs como referencia.
3. **Pulsen Generar**. La IA crea las preguntas con feedback en pocos segundos.
4. **Pulsen Vista previa** para ver el cuestionario en una pestaña nueva, exactamente como lo verán sus estudiantes. Si algo no les convence, regeneren.
5. **Pulsen Descargar HTML**. El archivo queda en su computadora con un nombre como `cuestionario-de-matematicas_20260520_2358.html`, listo para subir a donde lo necesiten.

## Características pensadas para el aula

- **Responsivo**: se ve perfecto en celular, tableta y computadora.
- **Imprimible**: con la función imprimir del navegador, se obtiene una versión limpia en papel con todas las respuestas y feedback visibles.
- **Barra de progreso y contador de aciertos** en tiempo real.
- **Pantalla de resultado final** con porcentaje y mensaje motivador según el desempeño.
- **Notación matemática profesional**: usa MathJax para renderizar fórmulas, así que pueden incluir expresiones como x², √, fracciones, etc.
- **Defensa anti-repetición**: tres capas que limpian automáticamente los casos en que la IA, ocasionalmente, entra en bucles de repetición en su respuesta.

## Limitaciones honestas

- **Máximo 10 preguntas por sesión**: para mantener la calidad del feedback. Si necesitan más, pueden generar varios cuestionarios y combinarlos.
- **La IA puede equivocarse**: aunque el modelo es robusto, siempre conviene que ustedes revisen las preguntas antes de entregarlas a los estudiantes. La vista previa está diseñada para eso.
- **Requiere conexión a Internet** mientras se generan las preguntas (después, el HTML descargado funciona sin conexión).
- **Los temas matemáticos especializados** o de gran abstracción pueden requerir varias iteraciones para obtener un resultado satisfactorio.

## Filosofía del proyecto

Este generador es parte de un esfuerzo más amplio por democratizar el acceso a recursos educativos de calidad para los estudiantes hispanohablantes que persiguen el GED. Fue creado pensando en colegas profesores que, como yo, dedican tiempo voluntario a esta causa, y que merecen herramientas profesionales que les ahorren horas de trabajo manual.

Es de código abierto y de uso libre. Si lo encuentran útil, compártanlo con otros profesores. Si lo mejoran, abran un *pull request* o envíenme sus ideas.

## Créditos y agradecimientos

- **Desarrollo y diseño pedagógico**: Prof. José M. Fernández (Zhema), ABE/ASE Math Master Teacher, Harry S. Truman College – City Colleges of Chicago.
- **Asistencia técnica**: Claude (Anthropic).
- **Modelo de IA**: Llama 3.3 70B (Meta), servido mediante la API gratuita de Groq.
- **Tipografía accesible**: Atkinson Hyperlegible (Braille Institute) y Lexend.
- **Renderizado matemático**: MathJax.

## Licencia

Este proyecto se distribuye bajo licencia abierta para uso educativo. Pueden usarlo, adaptarlo y compartirlo libremente, citando la fuente.

---

**Parte de [GEDparaHispanos.com](https://gedparahispanos.com)** — una iniciativa educativa gratuita para apoyar a los estudiantes hispanohablantes que persiguen su GED.
