# Zotero Hook

**Conecta tus lecturas. Construye tu criterio.**

Zotero Hook es una extensión experimental en español para **Zotero 10.0.x**, orientada a la lectura informada y al pensamiento crítico en el estudio, la investigación y la docencia.

[**Descargar el instalador más reciente (.xpi)**](https://github.com/tmarquez-mx/zotero-hook-releases/releases/latest/download/zotero-hook.xpi) · [Ver versiones](https://github.com/tmarquez-mx/zotero-hook-releases/releases)

Este repositorio publica instaladores y documentación de uso. El repositorio de desarrollo se mantiene privado.

## Instalación

1. Descarga el archivo `.xpi` del enlace anterior. No descargues los archivos «Source code» que GitHub genera para cada entrega.
2. En Zotero, abre **Herramientas → Plugins** (o **Extensiones**, según el idioma).
3. Pulsa **⚙ → Instalar plugin desde archivo…** y selecciona el `.xpi`. También puedes arrastrarlo a la ventana de plugins.
4. Reinicia Zotero. La primera entrega de este canal es **0.4.25**.

Si ya tienes Zotero Hook, instala esta versión sobre la anterior, sin desinstalarla. Guarda primero como notas las respuestas que quieras conservar: el historial es temporal.

## Empezar a usarlo

1. Abre un PDF o selecciona una fuente en tu biblioteca. Abre **Zotero Hook** desde su icono en el panel derecho.
2. Pulsa **Cambiar conexión**, elige el servicio, consulta los modelos y pulsa **Probar y usar conexión**. Puedes empezar con **Simulación**, sin enviar tus lecturas a un modelo.
3. Elige una función o escribe tu pregunta. Puedes añadir hasta seis lecturas y delimitar el texto mediante páginas, subrayados o un pasaje seleccionado.
4. Revisa la respuesta, su alcance y los fragmentos citados. Edita el resultado y guárdalo como una nota de Zotero si quieres conservarlo.

| Área | Qué puedes hacer |
|---|---|
| **Estudio** | Dialogar sobre un texto, explorar conceptos, examinar argumentos, resumir, comparar lecturas y preparar exposiciones. |
| **Investigación** | Valorar una fuente respecto de tu pregunta de investigación y recibir retroalimentación sobre tus notas. |
| **Docencia** | Elaborar guías de lectura, preparar sesiones y organizar unidades del curso. |

La **Guía de acceso rápido**, incluida en el plugin, ofrece los pasos completos y funciona sin conexión.

## Conectar un modelo

- **Groq u OpenRouter:** requieren tu propia API key. Las cuotas, precios y disponibilidad dependen del servicio y de tu cuenta.
- **LM Studio u Ollama:** requieren un servidor local activo y un modelo compatible.
- **Laboratorio IBERO · InferNode:** requiere credenciales del laboratorio y acceso a la red institucional o VPN.

Las claves se mantienen en memoria durante la sesión. Las consultas envían al servicio elegido el contexto preparado para la tarea; no envían automáticamente toda la biblioteca. Revisa el alcance antes de consultar.

## Actualizaciones

Después de instalar **0.4.25 o una versión posterior de este canal**, Zotero puede recibir las siguientes versiones automáticamente si permites las actualizaciones del plugin. Para comprobarlas manualmente, abre **Herramientas → Plugins → ⚙ → Buscar actualizaciones**.

Las versiones anteriores deben actualizarse manualmente una vez para incorporar este canal público. Si Zotero solicita reiniciar después de una actualización, hazlo.

## Alcance y ayuda

Las respuestas requieren revisión: una referencia existente no garantiza una interpretación correcta. Hook trabaja con texto extraíble; no hace OCR ni interpreta visualmente figuras. La versión 0.4.25 conserva las funciones de 0.4.24 y añade el canal público de actualización.

Para informar un problema, usa [Issues](https://github.com/tmarquez-mx/zotero-hook-releases/issues) e indica la versión de Zotero, la de Hook, el sistema operativo y los pasos para reproducirlo. No publiques claves ni textos privados.

Proyecto de **Teresa Márquez**. Consulta las [condiciones de uso](LICENSE).
