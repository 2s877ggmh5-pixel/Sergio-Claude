# Tarjeta de aplicación: Copilot Chat de GitHub

Obtenga información sobre cómo usar GitHub Copilot Chat de forma responsable mediante la comprensión de sus propósitos, funcionalidades y limitaciones.

## ¿Qué es una tarjeta de aplicación?

<!-- Do not modify this text.-->

GitHub’s application and platform cards are intended to help you understand how our AI technology works, the choices application owners can make that influence application performance and behavior, and the importance of considering the whole application, including the technology, the people, and the environment. Application cards are created for AI applications and platform cards are created for AI platform services. These resources can support the development or deployment of your own applications and can be shared with users or stakeholders impacted by them.

As part of its commitment to responsible AI, GitHub adheres to Microsoft's [six core principles](https://www.microsoft.com/en-us/ai/principles-and-approach/?msockid=3da790040c776d6f2b5485e40de56c06#ai-principles): fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability. These principles are embedded in the [Responsible AI Standard](https://cdn-dynmedia-1.microsoft.com/is/content/microsoftcorp/microsoft/final/en-us/microsoft-brand/documents/Microsoft-Responsible-AI-Standard-General-Requirements.pdf?culture=en-us\&country=us), which guides teams in designing, building, and testing AI applications. Application and Platform Cards play a key role in operationalizing these principles by offering transparency around capabilities, intended uses, and limitations. For further insight, readers are encouraged to explore Microsoft’s [Responsible AI Transparency Report](https://cdn-dynmedia-1.microsoft.com/is/content/microsoftcorp/microsoft/msc/documents/presentations/CSR/Responsible-AI-Transparency-Report-2025-vertical.pdf) and [Términos de GitHub](/es/site-policy/github-terms).

## 1. Información general

GitHub Copilot Chat es una interfaz de chat que le permite interactuar con GitHub Copilot formular y recibir respuestas a preguntas relacionadas con la codificación. GitHub Copilot Chat está disponible en GitHub.com, en los IDE admitidos (VS Code, Visual Studio, JetBrains y Eclipse), en GitHub Mobile y en Terminal Windows. En GitHub.com y en GitHub Desktop, Copilot también puede generar resúmenes de solicitudes de incorporación de cambios y mensajes de confirmación: información general basada en inteligencia artificial de los cambios realizados en una solicitud de incorporación de cambios o confirmación.

**Copilot Cloud**: Copilot en la nube (GitHub Copilot en GitHub.com, GitHub Mobile o en cualquier lugar en el que se seleccione "Nube" como entorno de sesión) puede responder a preguntas sobre los repositorios, planear y realizar cambios, revisar o crear solicitudes de incorporación de cambios y automatizar tareas de repositorio. Una única interfaz basada en el SDK de Copilot combina el chat y el trabajo agéntico.

GitHub Copilot Chat puede responder a una amplia gama de preguntas relacionadas con la codificación en temas como sintaxis, conceptos de programación, casos de prueba, depuración, etc. GitHub Copilot Chat no está diseñado para responder a preguntas no codificantes ni proporcionar información general sobre temas fuera de la codificación.

El idioma principal admitido para gitHub Copilot Chat es inglés.

## 2. Términos clave

En la lista siguiente se proporciona un glosario de términos clave relacionados con gitHub Copilot Chat:

* **Filtrado de contenido**: un sistema de seguridad que examina las solicitudes y respuestas para detectar y bloquear contenido dañino antes de que se muestre al usuario.
* **Hallucinación**: un fenómeno en el que un modelo de lenguaje genera una salida que suena factible, pero es incorrecta, no admitida por el contexto proporcionado o completamente fabricada. Las alucinaciones son un riesgo conocido de los modelos lingüísticos de gran tamaño y son una de las razones por las que es importante la revisión humana del contenido generado por la IA.
* **Modelo de lenguaje grande (LLM):** un tipo de red neuronal entrenada en un gran cuerpo de datos de texto que puede generar, analizar y transformar el lenguaje natural y el código. GitHub Copilot Chat usa una o varias LLM para procesar mensajes y generar respuestas.
* **Prompt**: entrada que se proporciona a GitHub Copilot Chat. El sistema combina el mensaje con contexto adicional (por ejemplo, abrir archivos o datos de repositorio) antes de enviarlos al modelo de lenguaje.
* **Coincidencia con código público**: Una característica que comprueba si las sugerencias de Copilot coinciden con código disponible públicamente. Dependiendo de la configuración, las sugerencias coincidentes pueden estar activadas o desactivadas; si esta opción está activada, las sugerencias pueden bloquearse o anotarse con una referencia al repositorio de origen y la información sobre la licencia correspondiente.
* **Resumen de la solicitud** de incorporación de cambios: información general generada por ia de los cambios en una solicitud de incorporación de cambios, que consta de un párrafo de prosa y una lista con viñetas de los cambios clave vinculados a los archivos afectados. Los resúmenes se generan a petición en GitHub.com.
* **Red teaming**: una práctica de pruebas estructurada en la que los evaluadores intentan deliberadamente provocar un comportamiento inseguro, dañino o no deseado en un sistema de IA. El Red Teaming ayuda a identificar vulnerabilidades y a mejorar las medidas de seguridad antes y después del lanzamiento.
* **Datos de entrenamiento**: el gran volumen de texto y código disponible públicamente que se utilizó para entrenar los modelos fundacionales en los que se basa GitHub Copilot Chat. La composición de los datos de entrenamiento influye en la calidad y cobertura de las sugerencias del modelo en diferentes lenguajes de programación, marcos y temas.

## 3. Características o funcionalidades clave

Las características y capacidades clave que se describen aquí indican para qué está diseñado GitHub Copilot Chat y cómo funciona en las tareas compatibles.

* **Asistencia conversacional para programar**: GitHub Copilot Chat proporciona una interfaz de lenguaje natural para hacer preguntas relacionadas con la programación y recibir respuestas en forma de código, explicaciones o instrucciones paso a paso. Los usuarios pueden formular preguntas de seguimiento para refinar las respuestas y el historial de conversaciones se mantiene dentro de una sesión.
* **Respuestas basadas en el contexto**: GitHub Copilot Chat utiliza información contextual, como los archivos abiertos, el repositorio activo, el historial del chat y, cuando está habilitado, los resultados de búsqueda en la web, para generar respuestas relevantes para la tarea actual del usuario. El contexto específico disponible depende de la plataforma (GitHub.com, IDE, Mobile, Terminal Windows o GitHub Desktop).
* **Disponibilidad multiplataforma**: GitHub Copilot Chat está disponible en varios entornos, como GitHub.com, los IDE compatibles (VS Code, Visual Studio, JetBrains y Eclipse), GitHub Mobile, Terminal Windows y GitHub Desktop. Cada plataforma ofrece una experiencia adaptada optimizada para su entorno.
* **Agent mode**: En los IDE admitidos, GitHub Copilot Chat puede funcionar en modo agente, donde el modelo planea de forma autónoma tareas de varios pasos, invoca herramientas (como ejecutar comandos de terminal o archivos de edición) e itera en los resultados. Esto amplía la experiencia de chat más allá de las interacciones de preguntas y respuestas de un solo turno.
* **Copilot Spaces**: Spaces permite a los usuarios organizar repositorios, archivos, problemas y otros materiales en una colección de contexto seleccionada. Cuando se hace una pregunta dentro de un espacio, Copilot usa el contexto incluido para generar respuestas más dirigidas y relevantes. También se puede acceder a espacios desde el IDE a través del servidor MCP de GitHub remoto.
* **Resúmenes de solicitudes de extracción**: En GitHub.com, Copilot puede generar un resumen generado por IA de los cambios en una solicitud de extracción. La salida consta de una descripción general en prosa seguida de una lista con viñetas de los cambios clave vinculados a los archivos afectados. Los resúmenes se generan a petición y están diseñados para ayudar a los revisores a comprender rápidamente qué ha cambiado.
* **Commit message generation**: On GitHub.com and in GitHub Desktop, Copilot puede generar un resumen de confirmación sugerido (título) y una descripción en función de los cambios de código seleccionados. En GitHub Escritorio, los usuarios pueden seleccionar líneas específicas de código o archivos para mejorar el contexto y la precisión. Los mensajes generados se pueden revisar y editar antes de confirmar.
* **Bring Your Own Key (BYOK)**: Las organizaciones pueden conectarse GitHub Copilot Chat a modelos de lenguaje de gran tamaño de proveedores de terceros compatibles proporcionando su propia clave de API, en lugar de usar el modelo hospedado GitHub predeterminado.
* **Content filtering**: En ocasiones, gitHub Copilot Chat puede incluir un sistema de filtrado de contenido que examina las solicitudes y respuestas para detectar y bloquear contenido dañino. Una característica de coincidencia de código público comprueba si las sugerencias coinciden con el código disponible públicamente y, en función de la configuración, bloquea o anota esas coincidencias con la información de origen y licencia.

## 4. Usos previstos

GitHub Copilot se puede usar en varios escenarios en una variedad de sectores. Algunos ejemplos de casos de uso incluyen:

* **Answering code questions**: Pregunte a GitHub Copilot Chat para obtener ayuda o aclaración sobre problemas de codificación específicos y recibir respuestas en formato de lenguaje natural o fragmento de código. La respuesta puede basarse en los datos de entrenamiento del modelo, el contexto del repositorio y los resultados de búsqueda en la web (cuando está habilitado).
* **Explicación del código y sugerencias de mejoras**: genere descripciones de lenguaje natural de propósito, entradas, salidas y dependencias de una función. GitHub Copilot Chat también puede sugerir mejoras como un mejor control de errores o un flujo de control más legible. Tenga en cuenta que las explicaciones generadas no siempre pueden ser precisas o completas y deben revisarse.
* **Generating unit test cases**: GitHub Copilot Chat puede ayudar a escribir casos de prueba unitaria mediante la generación de fragmentos de código basados en el código abierto en el editor o un fragmento de código resaltado. Puede sugerir posibles parámetros de entrada, valores de salida esperados y aserciones en función de la firma y el cuerpo de la función. GitHub Copilot Chat también puede sugerir casos de prueba para casos perimetrales y condiciones de límite, como el control de errores, los valores NULL o los tipos de entrada inesperados, que pueden ser difíciles de identificar manualmente. Es posible que los casos de prueba generados no cubran todos los escenarios posibles; Las pruebas manuales y la revisión de código siguen siendo necesarias.
* **Proponer correcciones de código**: obtenga correcciones sugeridas para errores en función del mensaje de error, la sintaxis de código y el contexto circundante. GitHub Copilot Chat puede sugerir cambios en variables, estructuras de control o llamadas de función que podrían resolver el problema. Tenga en cuenta que es posible que las correcciones sugeridas no siempre sean óptimas o completas.
* **Planificación de tareas de programación**: Leer y resumir incidencias de GitHub, responder preguntas sobre estas o proponer los siguientes pasos.
* **Obtener información sobre versiones, discusiones y confirmaciones**: resuma lo que ha cambiado en una versión, el gist de una discusión o los cambios en una confirmación específica.
* **Resumir los cambios de una pull request (GitHub.com)**: Genera un resumen generado por IA de los cambios de una pull request, que incluye una descripción general en texto y una lista con viñetas de los cambios clave enlazados a los archivos afectados, para ayudar a los revisores a comprender rápidamente qué ha cambiado y dónde centrar su revisión.
* **Generación de mensajes de confirmación (GitHub.com y GitHub Desktop)**: Genere un resumen (título) y una descripción del mensaje de confirmación a partir de los cambios de código que ha seleccionado para confirmar, lo que le ayudará a ahorrar tiempo y mantener historiales de confirmaciones claros. En GitHub Escritorio, puede seleccionar líneas de código o archivos específicos para mejorar la comprensión del contexto para aumentar la precisión. Puede revisar y editar el título y la descripción sugeridos antes de confirmar.
* **Encontrar el comando adecuado (Terminal Windows)**: Pide a Copilot que te sugiera comandos para realizar tareas en la línea de comandos. Puede revisar la pregunta hasta que el comando devuelto cumpla sus expectativas y, a continuación, insertarlo en la línea de comandos para ejecutarlo.
* **Explicar un comando desconocido (Terminal de Windows)**: Pide a Copilot que genere una descripción en lenguaje natural de la funcionalidad de un comando, incluidos sus parámetros de entrada y salida, y ejemplos de uso. Tenga en cuenta que es posible que las explicaciones generadas no siempre sean precisas o completas.
* **Desarrollo de una nueva característica (Spaces)**: Agrupación de código relevante, especificaciones de producto y notas de diseño en un espacio para que Copilot pueda explicar la implementación actual, resaltar huecos y redactar código nuevo o pasos siguientes.
* **Definir lógica para tareas repetidas (Espacios): documente** un proceso una vez (con diagramas de flujo, ejemplos o esquemas) y reutilíquelo en todo el equipo para patrones coherentes y plantillas reutilizables.
* **Compartir conocimientos con los miembros del equipo (Spaces)**: recopila el código y la documentación más recientes en un solo lugar para que Copilot pueda explicar sistemas, responder preguntas y facilitar la incorporación de nuevos miembros del equipo.

## 5. Modelos y datos de entrenamiento

GitHub Copilot aprovecha una variedad de modelos de inteligencia artificial para impulsar la experiencia que ven los usuarios. Para obtener una comparación de los modelos disponibles para Copilot, consulte [Comparación de modelos de IA](/es/copilot/reference/ai-models/model-comparison). Para obtener la lista completa de modelos admitidos, consulte [Modelos de IA admitidos en GitHub Copilot](/es/copilot/reference/ai-models/supported-models). Para obtener información sobre dónde se hospedan los modelos, consulte [Hospedaje de modelos para GitHub Copilot](/es/copilot/reference/ai-models/model-hosting). Para obtener más información sobre los datos utilizados para entrenar los modelos fundacionales en los que se basa GitHub Copilot Chat, consulte la comparación enlazada de modelos de IA anterior y [¿Con qué datos se ha entrenado GitHub Copilot?](https://github.com/features/copilot#faq) en las Preguntas frecuentes de GitHub Copilot.

### Uso de Bring Your Own Key (BYOK)

Al usar Bring Your Own Key con GitHub Copilot Chat, puede conectar la experiencia de chat a modelos de lenguaje de gran tamaño de proveedores compatibles más allá del modelo de Copilot predeterminado. Entre los ejemplos de proveedores admitidos se incluyen Anthropic, AWS Bedrock, Google AI Studio, Microsoft Foundry, OpenAI, proveedores compatibles con OpenAI y xAI. Agregue la clave de API para el proveedor elegido directamente en la configuración de Copilot.

Cuando BYOK está activo:

* **Ámbito de la funcionalidad**: el modelo elegido se usa en GitHub Copilot Chat. En el modo Agente, BYOK potencia la conversación principal, pero ciertas acciones, como la aplicación de código u otras llamadas a herramientas, pueden seguir usando modelos integrados Copilot optimizados para esas tareas. Estos modelos integrados no se ejecutan a través del proveedor BYOK.
* **Filtrado de contenido**: independientemente de qué proveedor esté activo, las respuestas siguen pasando por la API de GitHub y pueden someterse a un filtrado de contenido antes de que se te muestren los resultados.
* **Consideraciones de calidad**: las sugerencias pueden variar en función de las fortalezas y la cobertura de entrenamiento de su proveedor elegido.
* **Control de datos**: al usar BYOK, las solicitudes y respuestas se transmiten al proveedor seleccionado y pueden estar sujetas a las directivas de privacidad y retención de datos de ese proveedor.
* **Sus responsabilidades**: Usted es responsable de lo siguiente:
  * Seguridad de la clave de API del proveedor
  * Costos de uso o cuotas
  * Validación de salida
  * Evaluación de si el modelo elegido cumple los requisitos de seguridad y calidad
  * Cumplimiento de los términos del proveedor seleccionado
  * Determinar si el modelo elegido cumple con las leyes aplicables
  * Asegurarse de que un usuario revisa cualquier salida antes de usarla para tomar decisiones que afecten a las personas
* **Restricciones de exportación**: determinados modelos de IA pueden estar sujetos a controles de exportación. Compruebe que el proveedor y el modelo seleccionados están autorizados para su uso en su jurisdicción.

BYOK permite a su organización elegir el modelo de lenguaje que mejor se adapte a sus necesidades. Tenga en cuenta que las características de seguridad y rendimiento del modelo dependen del proveedor.

## 6. Rendimiento

GitHub Copilot Chat funciona mediante una combinación de procesamiento de lenguaje natural y aprendizaje automático para comprender su pregunta y proporcionarle una respuesta. Este proceso implica:

1. **Procesamiento de entrada**: el sistema procesa previamente el mensaje del usuario, combinado con información contextual (por ejemplo, el repositorio actual, los archivos abiertos o el historial de chat) y se envía a un modelo de lenguaje grande. La entrada del usuario puede adoptar la forma de fragmentos de código o lenguaje sin formato.
2. **Análisis del modelo de lenguaje**: el mensaje se pasa a través del modelo de lenguaje, que es una red neuronal entrenada en un gran cuerpo de datos de texto. El modelo de lenguaje analiza la solicitud de entrada.
3. **Generación de respuesta**: el modelo genera una respuesta basada en su análisis del mensaje de entrada y el contexto proporcionado. Esta respuesta puede adoptar la forma de código generado, sugerencias de código o explicaciones del código existente.
4. **Formato de salida**: La respuesta se formatea con resaltado de sintaxis, sangría y otras características para mayor claridad. En función del tipo de pregunta, también se pueden proporcionar vínculos al contexto que usa el modelo( como archivos de código fuente, problemas o documentación).

### Diferencias por experiencia

* **On GitHub.com**: el modelo puede recopilar contexto adicional de los datos del repositorio almacenados en GitHub y resultados de búsqueda web (cuando el administrador lo ha habilitado). Las respuestas pueden incluir vínculos a archivos de código fuente, problemas o documentación.
* **Resúmenes de solicitudes de extracción (GitHub.com)**: Cuando un usuario solicita un resumen, un flujo de trabajo usa las diferencias de código entre archivos para elaborar una indicación y le pide a Copilot que genere un resumen general. La salida consta de un párrafo de prosa que proporciona información general sobre los cambios, seguido de una lista con viñetas de cambios clave vinculados a las líneas de código respectivas. Puede generar un resumen en la descripción de una solicitud de incorporación de cambios nueva o existente, o en un comentario en la escala de tiempo de la solicitud de incorporación de cambios. Las solicitudes de incorporación de cambios más grandes pueden tardar hasta un par de minutos en procesarse. El único idioma admitido para los resúmenes de solicitudes de incorporación de cambios es inglés.
* **Commit message generation (GitHub.com)**: Al hacer clic en el botón **Commit changes** en GitHub.com, Copilot genera un resumen sugerido (título) y una descripción en función de los cambios de código en los archivos seleccionados. El texto se inserta en los campos de resumen y descripción para que revise y edite antes de confirmar. El único idioma admitido para la generación de mensajes de confirmación es inglés.
* **Commit message generation (GitHub Desktop)**: Al hacer clic en el botón Copilot en GitHub Desktop, Copilot genera un resumen sugerido (título) y una descripción en función de los cambios de código que ha seleccionado. Puede seleccionar líneas de código o archivos específicas para mejorar el contexto y la precisión, y puede volver a generar sugerencias antes de finalizar. El único idioma compatible es el inglés.
* **En el IDE**: el sistema combina la entrada del usuario con información contextual, como el nombre del repositorio y los archivos que el usuario ha abierto. En VS Code y Visual Studio, se puede proporcionar contexto adicional automáticamente desde un archivo opcional `.github/copilot-instructions.md` (el usuario puede deshabilitarlo en la configuración). Al usar el participante de chat de `@github` en VS Code o Visual Studio, GitHub Copilot Chat también puede recopilar contexto del código almacenado en GitHub y de los resultados de búsqueda de Bing (si está habilitado por el administrador).
* **On GitHub Mobile**: el mensaje de entrada se procesa previamente y se envía al modelo de lenguaje. El sistema solo está pensado para responder a preguntas relacionadas con la codificación. Las opciones disponibles varían según Copilot plan: los usuarios con una suscripción de Copilot Enterprise pueden tener conversaciones mediante datos de repositorios indexados privados y, si la integración de búsqueda web está habilitada, reciba respuestas informadas por los resultados de búsqueda web. Los usuarios con una suscripción de Copilot Pro pueden analizar los repositorios públicos más populares.
* **In Terminal Windows**: el mensaje del usuario se combina con información contextual (el nombre del shell activo y el historial de chat) y se envía al modelo de lenguaje. Las respuestas toman la forma de un comando sugerido o una explicación de un comando. Los comandos sugeridos no se ejecutan automáticamente; debe hacer clic en un comando para insertarlo en la línea de comandos y, a continuación, ejecutarlo manualmente.
* **In Copilot Spaces**: Spaces le permite organizar el contexto que usa GitHub Copilot Chat para responder a sus preguntas. Un espacio puede incluir repositorios, código, solicitudes de incorporación de cambios, problemas, contenido de texto libre, como transcripciones o notas, imágenes y cargas de archivos. Cuando envías una pregunta en un espacio, Copilot amplía tu solicitud con contexto relevante de ese espacio. También se puede acceder a espacios desde el IDE a través del servidor MCP de GitHub remoto. No todo el contenido de un espacio se usa en todas las respuestas: Copilot procesa una parte del contenido incluido, por lo que ser selectivo sobre lo que agrega ayuda a garantizar la relevancia.

GitHub Copilot Chat está pensado para proporcionarle la respuesta más relevante a su pregunta. Sin embargo, es posible que no siempre proporcione la respuesta que buscas. Los usuarios de GitHub Copilot Chat son responsables de revisar y validar las respuestas generadas por el sistema para asegurarse de que son precisas y adecuadas.

## 7. Limitaciones

Comprender las limitaciones de GitHub Copilot Chat es fundamental para determinar si se usa dentro de límites seguros y efectivos. Aunque animamos a los clientes a aprovechar gitHub Copilot Chat en sus soluciones o aplicaciones innovadoras, es importante tener en cuenta que gitHub Copilot Chat no se diseñó para todos los escenarios posibles. Animamos a los usuarios a hacer referencia a [Términos de GitHub](/es/site-policy/github-terms) , así como a las siguientes consideraciones al elegir un caso de uso:

* **Ámbito delimitado**: GitHub Copilot Chat se ha entrenado en un gran cuerpo de código, pero es posible que no pueda controlar estructuras de código más complejas ni lenguajes de programación ocultos. Para cada idioma, la calidad de las sugerencias depende del volumen y la diversidad de los datos de entrenamiento. Por ejemplo, JavaScript está bien representado y bien compatible, mientras que los lenguajes menos comunes pueden producir resultados de menor calidad.
* **Posibles sesgos**: los datos de entrenamiento extraídos de repositorios de código existentes pueden contener sesgos y errores que la herramienta puede perpetuar. GitHub Copilot Chat también puede estar sesgado hacia ciertos lenguajes de programación o estilos de codificación, lo que puede dar lugar a sugerencias de código poco óptimas o incompletas.
* **Riesgos de seguridad**: el código generado puede exponer información confidencial o vulnerabilidades si no se revisa detenidamente. Revise y pruebe siempre el código generado exhaustivamente, especialmente para las aplicaciones sensibles a la seguridad.
* **Matches con código público**: aunque la probabilidad es baja, gitHub Copilot Chat puede generar código que coincida con el código del conjunto de entrenamiento. Debe tomar las mismas precauciones que con cualquier código que use material que no se originó de forma independiente, incluidas las pruebas rigurosas, el examen de IP y la comprobación de vulnerabilidades de seguridad. Para obtener más información, vea [Encontrar código público que coincida con las sugerencias de GitHub Copilot](/es/copilot/how-tos/copilot-in-your-ide/copilot-for-common-tasks/find-matching-code).
* **Código inexacto**: GitHub Copilot Chat puede generar código que parece válido, pero no es correcto desde el punto de vista semántico o sintáctico, o no refleja con precisión la intención del desarrollador. Revise detenidamente y pruebe el código generado, especialmente para aplicaciones críticas o confidenciales.
* **Respuestas inexactas sobre temas no relacionados con la programación**: GitHub Copilot Chat no está diseñado para responder preguntas no relacionadas con la programación, y sus respuestas en esos contextos pueden ser irrelevantes o absurdas.
* **Riesgo de comandos destructivos (Terminal Windows)**: Copilot puede sugerir comandos que podrían ser destructivos, como eliminar contenido o dar formato a un disco duro, lo cual puede ser necesario en determinados escenarios, pero puede causar problemas si se usa incorrectamente. En última instancia, es responsable de los comandos que elija ejecutar. A pesar de la existencia de mecanismos de protección y seguridad, la ejecución de comandos conlleva riesgos inherentes.
* **Lines ha modificado los límites para los resúmenes de PR (GitHub.com)**: Los archivos con más de 400 adiciones y eliminaciones combinadas quedan excluidos del resumen.
* **Los resúmenes de las solicitudes de incorporación de cambios no se actualizan automáticamente (GitHub.com)**: Los resúmenes de las solicitudes de incorporación de cambios solo se crean cuando los usuarios los solicitan manualmente. Cuando se realizan actualizaciones o cambios en la solicitud de incorporación de cambios, el resumen no se actualiza automáticamente. Los usuarios pueden solicitar un nuevo resumen, pero deben revisar cuidadosamente la salida actualizada, lo que conlleva los mismos riesgos de inexactitud que el original.
* **Replicación del contenido de pr (GitHub.com)**: dado que un resumen describe los cambios en una solicitud de incorporación de cambios, si los términos dañinos o ofensivos aparecen en el contenido de la solicitud de incorporación de cambios, es posible que el resumen replique esos términos. Los usuarios deben esperar que los términos utilizados en su PR aparezcan en el resumen generado por IA.
* **Ámbito delimitado para mensajes de confirmación (GitHub.com y GitHub Desktop)**: La generación de mensajes de confirmación puede tener problemas con cambios de código complejos, ventanas de diferencias cortas o lenguajes de programación desarrollados recientemente. La calidad de las sugerencias depende de la disponibilidad y la diversidad de datos de aprendizaje para los idiomas implicados.
* **Replicación del contenido de un commit (GitHub.com y GitHub Desktop)**: Dado que un mensaje de commit resume los cambios de un commit, si aparecen términos perjudiciales u ofensivos en los cambios de código, es posible que el mensaje generado incluya esos términos.
* **Los mensajes de commit no se actualizan automáticamente (GitHub.com y GitHub Desktop)**: Los mensajes de commit solo se generan cuando los solicitas. Al realizar cambios adicionales, el mensaje de confirmación no se actualiza automáticamente. Puede volver a generar una nueva sugerencia, pero debe revisar cuidadosamente la salida actualizada, lo que conlleva los mismos riesgos de inexactitud que el original.
* **Interpretación de la intención del usuario (Spaces)**: Spaces ayudan a basar las respuestas de GitHub Copilot Chat en un contexto seleccionado, pero el sistema puede seguir malinterpretando tu intención. Revisa siempre el resultado para asegurarte de que refleja tus objetivos.
* **Context limits (Spaces)**: Spaces tiene límites de tamaño definidos y GitHub Copilot Chat solo procesa una parte del contenido que incluya. No todos los archivos, documentos o notas de un espacio se usarán en una respuesta. Ser selectivo sobre lo que agrega ayuda a garantizar que se usa el contexto más relevante.
* **Rendimiento diferente en función del idioma**: GitHub Copilot Chat se ha optimizado principalmente para el inglés. Es posible que observe que el rendimiento es diferente con las indicaciones en otros idiomas.
* **Uso de la búsqueda web**: En GitHub.com y al usar el participante de chat de GitHub en IDE compatibles, GitHub Copilot Chat puede usar opcionalmente una búsqueda de Bing para ayudar a responder a tu pregunta; por ejemplo, consultas sobre eventos recientes, nuevas tecnologías o temas muy específicos. El administrador de la empresa puede habilitar o deshabilitar Bing para su organización. Cuando se utiliza la búsqueda en la web, el contenido de tu indicación, junto con el contexto adicional, se utiliza para generar una consulta de búsqueda de Bing en tu nombre. La consulta de búsqueda enviada a Bing se rige por [la Declaración de privacidad de Microsoft](https://privacy.microsoft.com/en-us/privacystatement). Para obtener más información, vea [Administración de directivas y características para GitHub Copilot en su empresa](/es/copilot/how-tos/administer-copilot/manage-for-enterprise/manage-enterprise-policies).

## 8. Evaluaciones

<!-- Do not modify this text.-->

Las evaluaciones de rendimiento y seguridad evalúan si las aplicaciones de inteligencia artificial funcionan de forma confiable y segura mediante el examen de factores como la base, la relevancia y la coherencia, a la vez que se identifican los riesgos de generar contenido dañino. Las siguientes evaluaciones se llevaron a cabo con componentes de seguridad ya implementados, que también se describen en [9. Componentes y mitigaciones de seguridad](#9-componentes-de-seguridad-y-mitigaciones).

### Evaluaciones de rendimiento y calidad

GitHub Copilot se evalúa en sus superficies admitidas mediante una combinación de pruebas comparativas estándar del sector (por ejemplo, SWE-Bench) y conjuntos de evaluación desarrollados internamente. Las tareas comparativas se obtienen de repositorios públicos de código abierto y escenarios sintéticos; no se usan consultas de usuario reales ni código de cliente. Cada evaluación incluye varias ejecuciones independientes para tener en cuenta el no determinismo en las salidas del modelo. Entre las métricas clave se incluyen la tasa de resolución (porcentaje de tareas completadas correctamente), la eficacia del token, la latencia y la confiabilidad de las llamadas a herramientas. Los modelos se vuelven a evaluar cuando se realizan y supervisan las actualizaciones continuamente en producción a través de tasas de error, latencia de respuesta y patrones de uso agregados.

### Métodos de evaluación de rendimiento y calidad

Los nuevos modelos para GitHub Copilot se someten a un proceso de evaluación por etapas antes de la implementación. Los equipos integradores ejecutan conjuntos de pruebas comparativas específicos de su superficie, probando el modelo en tareas de codificación representativas, como correcciones de errores, generación de código y refactorización de varios archivos. Los resultados se revisan con respecto a las líneas base establecidas y los modelos de producción existentes. Los modelos deben cumplir o superar el rendimiento de línea base en métricas clave, como la tasa de resolución, la eficacia del token y la latencia, antes de avanzar a la siguiente fase. Un comité de revisión multifuncional toma una decisión formal de seguir o no seguir antes de que se apruebe cualquier modelo para su despliegue de cara al usuario.

### Evaluaciones de riesgos y seguridad

<!-- Do not modify this text.-->

La evaluación de posibles riesgos asociados con el contenido generado por IA es esencial para protegerse frente a los riesgos de contenido con distintos grados de gravedad. Esto incluye la evaluación de la predisposición de una aplicación de inteligencia artificial hacia la generación de contenido dañino o la prueba de vulnerabilidades a ataques de jailbreak. Para GitHub, realizamos evaluaciones de rendimiento, incluidas las adaptadas para fines de codificación de [Microsoft Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/risk-safety-evaluators):

* Odio e injusticia
* Sexual
* Violencia
* Auto-daño
* Material protegido
* Desbloqueo
* Vulnerabilidad de código

### Datos de evaluación para la calidad y la seguridad

<!-- Do not modify this text.-->

Nuestros datos de evaluación están personalizados para evaluar el rendimiento de las aplicaciones de inteligencia artificial en áreas clave de **seguridad** y **calidad**, simulando escenarios y riesgos reales. Empezamos por identificar los aspectos de evaluación pertinentes basados en la investigación multidisciplinaria y la aportación de expertos. Estas preocupaciones se traducen en objetivos de evaluación específicos y guían la formulación de las métricas de evaluación. Para **safety**, creamos avisos adversarios para evitar respuestas no deseadas o de casos perimetrales, que luego se puntúan mediante anotadores asistidos por IA entrenados para evaluar la alineación con los estándares de GitHub. Para la **calidad**, elaboramos instrucciones basadas en rúbricas adaptadas a escenarios, incluida la evaluación de aplicaciones y agentes de generación aumentada con recuperación (RAG). Los conjuntos de datos se recopilan de diversos orígenes, incluidos los conjuntos de datos sintéticos y públicos, para simular escenarios de usuario reales. Con los conjuntos de datos seleccionados, ambas evaluaciones se someten a refinamiento iterativo y ajuste humano para mejorar la confiabilidad y eficacia de las métricas. Esta metodología constituye la base de evaluaciones repetibles y rigurosas que reflejan cómo los clientes usan las evaluaciones para crear una mejor inteligencia artificial.

### Evaluaciones personalizadas

Como parte de nuestro proceso de desarrollo de productos, llevamos a cabo ejercicios de red teaming para comprender y mejorar la seguridad de GitHub Copilot Chat. Cuando está habilitada, las indicaciones de entrada y las finalizaciones de salida se ejecutan a través de filtros de contenido.

## 9. Componentes de seguridad y mitigaciones

* **Filtrado de contenido**: cuando está habilitado, el sistema de filtrado de contenido detecta e impide la salida de contenido dañino. Si encuentra contenido ofensivo, notifique a `copilot-safety@github.com`.
* **Coincidencia de código público**: Según la configuración, es posible que GitHub Copilot Chat tenga activado o desactivado el filtro de detección de duplicados. Si está activado, GitHub Copilot Chat bloquea las sugerencias que coinciden con el código público o las anota con vínculos a los repositorios de origen y los detalles de la licencia. En VS Code, si ha habilitado sugerencias que coinciden con código público, GitHub Copilot Chat muestra un mensaje con un vínculo para mostrar el código coincidente y los detalles de la licencia en el editor. En Visual Studio, JetBrains, Eclipse y GitHub Mobile, GitHub Copilot Chat usa filtros que bloquean coincidencias con código público. Independientemente de la configuración, debe tomar las mismas precauciones que con cualquier código que use material que no se originó de forma independiente, incluidas las pruebas rigurosas, el examen de IP y la comprobación de vulnerabilidades de seguridad. Para obtener más información, vea [Encontrar código público que coincida con las sugerencias de GitHub Copilot](/es/copilot/how-tos/copilot-in-your-ide/copilot-for-common-tasks/find-matching-code).

## 10. Procedimientos recomendados para implementar y adoptar GitHub Copilot

La inteligencia artificial responsable es un compromiso compartido entre GitHub y sus clientes. Aunque GitHub crea aplicaciones de inteligencia artificial con seguridad, imparcialidad y transparencia en el núcleo, los clientes desempeñan un papel fundamental en la implementación y el uso de estas tecnologías de forma responsable dentro de sus propios contextos. Para admitir esta asociación, ofrecemos los siguientes procedimientos recomendados para los implementadores y los usuarios finales con el fin de ayudar a los clientes a implementar la inteligencia artificial responsable de forma eficaz.

* **Exercise precaución y evaluación de los resultados al usar gitHub Copilot Chat para decisiones consecuentes o en dominios confidenciales**: <!-- Do not modify this text.-->
  Las decisiones consecuentes son aquellas que pueden tener un impacto legal o significativo en el acceso de una persona a la educación, el empleo, las plataformas financieras, los beneficios gubernamentales, la salud, la vivienda, el seguro, las plataformas legales o que podrían dar lugar a daños físicos, psicológicos o financieros. Los dominios confidenciales, como las plataformas financieras, la atención sanitaria y la vivienda, requieren atención especial debido al potencial de impacto desproporcionada en diferentes grupos de personas. Al usar la inteligencia artificial para tomar decisiones en estas áreas, asegúrese de que las partes interesadas afectadas puedan comprender cómo se toman las decisiones, apelar decisiones y actualizar los datos de entrada pertinentes.

* **Evaluar consideraciones legales y normativas**: <!-- Do not modify this text.-->
  Los clientes deben evaluar posibles obligaciones legales y normativas específicas al usar cualquier plataforma y soluciones de inteligencia artificial, que puede que no sean adecuadas para su uso en todos los sectores o escenarios. Además, las plataformas o soluciones de inteligencia artificial no están diseñadas para y pueden no usarse de maneras prohibidas en términos de servicio aplicables y códigos de conducta pertinentes.

* **Ejercicio de la supervisión humana cuando proceda**: la supervisión humana es una protección importante al interactuar con las aplicaciones de inteligencia artificial. Aunque mejoramos continuamente nuestras aplicaciones de inteligencia artificial, la inteligencia artificial podría cometer errores. Los resultados generados pueden ser inexactos, incompletos, sesgados, desalineados o irrelevantes para los objetivos previstos. Esto podría ocurrir debido a varias razones, como la ambigüedad en las entradas o limitaciones de los modelos subyacentes. Por lo tanto, los usuarios deben revisar las respuestas generadas por GitHub Copilot Chat y comprobar que cumplen sus expectativas y requisitos.

* **Tenga en cuenta el riesgo de sobrecarga**: <!-- Do not modify this text.-->
  La dependencia excesiva de la inteligencia artificial se produce cuando los usuarios aceptan salidas de IA incorrectas o incompletas, principalmente porque los errores en las salidas de IA pueden ser difíciles de detectar. Para el usuario final, el exceso de dependencia podría dar lugar a una disminución de la productividad, la pérdida de confianza, el abandono de aplicaciones, la pérdida financiera, daños psicológicos, daños físicos, entre otros. (por ejemplo, un médico acepta una salida de IA incorrecta).

* **Tenga cuidado al diseñar inteligencia artificial agente en dominios confidenciales**: <!-- Do not modify this text.-->
  Los usuarios deben tener precaución al diseñar o implementar aplicaciones de inteligencia artificial agente en dominios confidenciales en los que las acciones del agente son irreversibles o muy consecuentes. También se deben tomar precauciones adicionales al crear inteligencia artificial agente autónoma, tal como se describe más adelante en [Términos de GitHub](/es/site-policy/github-terms).

* **Use gitHub Copilot Chat como herramienta, no como reemplazo**: aunque GitHub Copilot Chat puede ser una herramienta eficaz para generar código, es importante usarlo como herramienta en lugar de reemplazar la programación humana. Revise y pruebe siempre el código generado por GitHub Copilot Chat para asegurarse de que cumple sus requisitos y está libre de errores o problemas de seguridad.

* **Mantén las indicaciones centradas en el tema**: GitHub Copilot está diseñado para abordar consultas relacionadas con la codificación. Limitar las indicaciones a las preguntas o tareas de codificación mejora la calidad de salida del modelo.

* **Usar procedimientos de revisión de código y codificación seguros**: siga los procedimientos recomendados para la codificación segura(como evitar contraseñas codificadas de forma rígida o vulnerabilidades de inyección de código SQL) y revise todo el código generado.

* **Sé selectivo con el contexto (Spaces)**: añadir solo los archivos, repositorios y notas más relevantes a un espacio ayuda a Copilot a centrarse. La sobrecarga de un espacio con contenido innecesario puede diluir la calidad de respuesta.

* **Mantener el contexto actualizado (Spaces):** a medida que el proyecto evoluciona, actualice los archivos, los problemas o la documentación en el espacio. El contexto obsoleto puede provocar Copilot generar respuestas inexactas o incompletas.

* **Utiliza instrucciones junto con fuentes (Spaces)**: Combinar instrucciones en lenguaje natural con fuentes seleccionadas ayuda a Copilot a comprender mejor tu intención.

* **Anclar el chat en un espacio (Spaces)**: iniciar conversaciones desde dentro de un espacio garantiza la continuidad y la relevancia, manteniendo las respuestas alineadas con el contexto que has configurado.

* **Revisa los resúmenes de las solicitudes de incorporación de cambios antes de publicarlos (GitHub.com)**: Los resúmenes de las solicitudes de incorporación de cambios están pensados para complementar —no para sustituir— tu propio contexto sobre los cambios. Revise y evalúe siempre la precisión de un resumen generado antes de guardar o publicar la solicitud de incorporación de cambios.

* **Revisa los mensajes de confirmación antes de confirmar los cambios (GitHub.com y GitHub Desktop)**: La generación de mensajes de confirmación está pensada para complementar —no sustituir— tus propias descripciones de los cambios. Revise y edite siempre el título y la descripción sugeridos antes de confirmar. En GitHub Escritorio, seleccionar líneas de código o archivos específicas puede mejorar la precisión. Puede rechazar la generación de mensajes de confirmación a través de la página Copilot [settings](https://github.com/settings/copilot/features) en GitHub.com.

* **Proporcionar comentarios**: si encuentra algún problema o limitaciones, proporcione comentarios a través de los botones de arriba y abajo debajo de cada respuesta de chat. La capacidad de proporcionar comentarios sobre los resúmenes de solicitudes de incorporación de cambios depende de la configuración empresarial. Para obtener más información, vea [Administración de directivas y características para GitHub Copilot en su empresa](/es/copilot/how-tos/administer-copilot/manage-for-enterprise/manage-enterprise-policies). Para la generación de mensajes de confirmación, puede compartir comentarios a través de la discusión [community](https://github.com/orgs/community/discussions/categories/copilot-news-and-announcements) o [abrir un problema en el repositorio de GitHub Desktop](https://github.com/desktop/desktop/issues). Esto ayuda a mejorar la herramienta y abordar los problemas.

* **Mantente al día**: GitHub Copilot Chat está evolucionando. Manténgase al día con las actualizaciones, los nuevos riesgos de seguridad y los procedimientos recomendados.

## 11. Más información sobre gitHub Copilot Chat

Para obtener instrucciones adicionales sobre el uso responsable de GitHub Copilot Chat, se recomienda revisar la siguiente documentación:

* [Plantear preguntas a GitHub Copilot en tu IDE](/es/copilot/how-tos/copilot-in-your-ide/chat-with-copilot/chat-in-ide)
* [Creación de un resumen de solicitudes de incorporación de cambios con GitHub Copilot](/es/enterprise-cloud@latest/copilot/how-tos/copilot-on-github/copilot-for-github-tasks/create-a-pr-summary)
* [Hacer preguntas a GitHub Copilot en GitHub](/es/enterprise-cloud@latest/copilot/how-tos/copilot-on-github/chat-with-copilot/chat-in-github)
* [Terminal Chat](https://learn.microsoft.com/windows/terminal/terminal-chat)
* [Términos de licencia de la versión preliminar de GitHub](/es/site-policy/github-terms/github-pre-release-license-terms)
* [Términos de GitHub para productos y funciones adicionales](/es/site-policy/github-terms/github-terms-for-additional-products-and-features#github-copilot)
* [Centro de confianza de GitHub Copilot](https://copilot.github.trust.page/)

### Obtener más información sobre la IA responsable

* [Principios de inteligencia artificial de Microsoft](https://www.microsoft.com/en-us/ai/responsible-ai)
* [Recursos de inteligencia artificial responsable de Microsoft](https://www.microsoft.com/en-us/ai/responsible-ai-resources)
* [Cursos de Microsoft Azure Learning sobre IA responsable](https://docs.microsoft.com/en-us/learn/paths/responsible-ai-business-principles/)
