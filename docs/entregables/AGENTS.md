# AGENTS.md — /docs/entregables

Ver también [`/docs/AGENTS.md`](../AGENTS.md) y el [`AGENTS.md` de la raíz](../../AGENTS.md).

## Qué hay acá

Documentos terminados, con diseño, pensados para **enviarse o presentarse directamente al cliente** (Antonela, Florencia Yacante). Distinto del resto de `/docs`, que es documentación interna de trabajo del equipo DOOH.

## Reglas específicas

- **Nada de jerga interna del equipo** en el texto visible: sin referencias a "nuestro research", nombres de archivos internos, ni notas tipo "pendiente de confirmar con Fernanda". Lo que es proceso interno queda en `/docs` (nivel raíz), no acá.
- **HTML autocontenido:** estos entregables son archivos `.html` standalone — fuentes embebidas en base64 (`@font-face` con `data:font/woff2;base64,...`), sin dependencias externas (CDNs, fuentes de Google Fonts por URL, imágenes remotas). Deben poder abrirse localmente sin conexión y verse igual.
- **Layout tipo página impresa (A4):** el patrón ya establecido usa `.page { width:210mm; min-height:297mm; }` con `page-break-after:always` — mantenerlo si se agregan secciones nuevas, para que el documento siga funcionando bien tanto en pantalla como exportado a PDF.
- **Antes de agregar contenido nuevo a un entregable existente:** revisar que no contradiga ni duplique lo ya validado con el cliente en `/docs` (nivel raíz) — estos documentos deben reflejar el estado más actualizado y confirmado del proyecto, no una versión de trabajo intermedia.
- Cuando se identifique un riesgo o dato sin confirmar dentro de un entregable (ej. un nombre candidato con riesgo de colisión de marca), presentarlo en tono bajo y como parte del proceso normal ("a chequear en la etapa de disponibilidad"), no como alerta urgente — el tono hacia el cliente es siempre calmo y profesional.
