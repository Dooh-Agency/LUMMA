# AGENTS.md — /docs

Reglas específicas para trabajar dentro de esta carpeta. Ver también el [`AGENTS.md` de la raíz](../AGENTS.md), que sigue aplicando.

## Qué hay acá

Toda la documentación del proyecto Lumma / 4D E-Motion. Tres subcarpetas con reglas propias:

- **[`brand/`](brand/AGENTS.md)** — material de marca fuente, provisto por el cliente. Solo lectura.
- **[`entregables/`](entregables/AGENTS.md)** — documentos que se envían o presentan al cliente. Reglas de formato/calidad más estrictas.
- **[`fuentes/`](fuentes/AGENTS.md)** — transcripciones y mails fuente primaria del cliente, en texto. Registro histórico, solo lectura. Ante contradicción con un resumen interno, prima la fuente.

## Mapa de documentos (nivel raíz de /docs)

**Vigentes (usar estos primero):**

| Documento | Para qué sirve |
|---|---|
| `Lumma_4D_EMotion_Base_Proyecto.md` | Fuente única de referencia del proyecto completo: contexto, cronología de comunicación con el cliente (incluye reuniones), alcance, presupuesto. Leer primero si hay que retomar contexto. |
| `Naming_Punto1_Kickoff.md` | Alcance y cronograma acordado específicamente para la etapa de Naming (Punto 1), más el mail de inicio formal. |
| `Territorio_Naming_Punto1_v2.md` | Auditoría de ADN de marca + territorio de naming operable, corregido tras la reunión del 2/sept (saca "Zen", ajusta filtro de competidores). |
| `Research_Competidores_Naming_v2.md` | Research de mercado, corregido: distingue competidores reales (D-BOX, 4DX, MX4D) de partners/proveedores (Inorca, Irwin) y de exhibidores/clientes (AMC, Regal, Cinemark) — estos últimos ya no cuentan como colisión de nombre. |
| `Mapa_Estructura_Productos_Lumma_v2.md` | Arquitectura de producto de Lumma (Core/Luxury/Recliner + Magnify 8/"+"), con la duda de "premium" cerrada y la tarea de "recliner en el nombre sí/no" agregada. |
| `Mail_Validacion_Contexto_Territorio.md` | Mail enviado a Antonela con el entregable HTML, pidiendo validación — histórico, ya cumplió su función (la reunión del 2/sept fue la respuesta). |
| `Consolidado_Naming_Punto1_Avance.md` | Resumen ejecutivo de avance al 17/8, pensado para reuniones de estado. Contiene hallazgos de competidores ya superados por la v2 — al citarlo, preferir los datos de la v2. |
| `Ronda_Nombres_Luxury_Recliner.md` | Ronda de generación de nombres, curada (chequeo lingüístico ES/EN/PT aplicado, "Prime" asignado a Recliner, justificación de "recliner en el nombre" resuelta). Base del segundo entregable. |
| `Avance_Naming_Consolidado.html` | Documento interno consolidado (post reunión 2/sept) para compartir con el equipo por WhatsApp/mobile. No es entregable de cliente. Resume territorio v2 + ronda de nombres. |
| `entregables/Lumma_Ajustes_y_Tanda_de_Nombres.html` | **Segundo entregable de cliente** — ajustes incorporados de la reunión del 2/sept + primera tanda de nombres curada + análisis "recliner en el nombre sí/no". Mismo estilo visual que el primer entregable. |

**Históricos (no editar, solo consultar si hace falta ver el razonamiento previo):**

| Documento | Reemplazado por |
|---|---|
| `Territorio_Naming_Punto1.md` (v1) | `Territorio_Naming_Punto1_v2.md` |
| `Research_Competidores_Naming.md` (v1) | `Research_Competidores_Naming_v2.md` |
| `Mapa_Estructura_Productos_Lumma.md` (v1) | `Mapa_Estructura_Productos_Lumma_v2.md` |
| `Naming_Territorio.md` | Versión de Fernanda del territorio — su contenido relevante ya está reconciliado en la v2 |
| `Mail_Preguntas_Arquitectura_Productos.md` | Consulta puntual ya resuelta, mantenido solo como registro |

## Convenciones

- Nombres de archivo en `PascalCase_Con_Guiones_Bajos.md`, en español.
- Cada documento nuevo debe abrir con una línea que diga a qué otros documentos complementa/reemplaza (patrón ya usado en todos los archivos existentes).
- Antes de crear un documento nuevo, revisar si el contenido encaja mejor como sección de uno ya existente — este proyecto tiende a generar muchos documentos cortos que se vuelven difíciles de navegar; consolidar cuando sea razonable.
- **Versionado (`_v2`, `_v3`, ...):** cuando una corrección cambia una conclusión ya compartida con el cliente, crear un archivo nuevo con sufijo `_vN` en vez de editar el original — el archivo previo queda intacto como registro histórico, con una línea `📌 Versión histórica` al principio apuntando a la versión vigente. No usar este patrón para actualizaciones menores/incrementales (esas sí se editan directo, como siempre) — solo cuando se corrige algo ya enviado o presentado al cliente.
