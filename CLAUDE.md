# Perfil de despacho — Gerardo Saucedo
# Plugin: litigacion-gerardo-saucedo
# Origen: Formulario de Diagnóstico de Gerardo Saucedo (2026-06-29)

> Plantilla viva del despacho. Ajustar cualquier campo con `/customize` o rehacer con `/cold-start-interview`.

---

## Identidad del despacho

| Campo | Valor |
|---|---|
| Abogado / Despacho | Gerardo Saucedo |
| Forma jurídica | Abogado ejerciente individual |
| Colegio profesional | ICAS (Ilustre Colegio de Abogados de Sevilla) |
| Nº de colegiado | [PENDIENTE — indicar] |
| Provincia de actuación | Sevilla |
| Años ejerciendo | 31 |
| Correo | [PENDIENTE] |
| Teléfono | [PENDIENTE] |

---

## Áreas de práctica

- **Civil** (incl. reclamaciones económicas, responsabilidad civil)
- **Penal** (defensa y acusación)
- **Familia**
- **Mercantil** (reclamaciones mercantiles)
- **Bancario** (derecho bancario)

> El plugin está orientado a **litigación civil, mercantil y de familia**. Los asuntos **penales** de Gerardo se asisten a nivel de estrategia/jurisprudencia/redacción, pero las skills de escritos siguen el cauce civil de la LEC.

### Asuntos más frecuentes
Reclamaciones económicas · responsabilidad civil · reclamaciones mercantiles · derecho bancario · asuntos penales (defensa y acusación).

---

## Clientes

| Campo | Valor |
|---|---|
| Perfil típico | Particulares y pymes |

---

## Rol y posición procesal

| Campo | Valor |
|---|---|
| Posición por defecto | Variable (Gerardo lleva tanto acusación/demandante como defensa/demandado) — preguntar por asunto |
| Derecho civil foral | N/A |

---

## Herramientas y tecnología

| Herramienta | Uso |
|---|---|
| Dropbox | Documentación — **conector MCP activo** en este plugin (`https://mcp.dropbox.com/mcp`) |
| Outlook | Correo |
| LexNET | Solo recibir notificaciones |
| Word | Redacción / entregables `.docx` |
| WhatsApp | Comunicación |
| El Derecho (Lefebvre) | Base de datos jurídica propia de Gerardo |
| Perplexity | IA que ya usa hoy |
| CRM / gestor de expedientes | **No tiene** |

### Organización documental
Carpetas por cliente en el ordenador + expediente en papel. Patrón de slug de expediente: `apellidos-tipo-año` (DEFAULT — ajustar con `/customize`).

---

## Jurisprudencia — conector Jurisprudenciator (ÚNICA vía)

- Toda búsqueda y verificación de jurisprudencia se hace con el **conector MCP `jurisprudenciator`** (`https://mcp.jurisprudenciator.lexiaipro.org/mcp`): cubre CENDOJ (TS, AN, AP, TSJ). **No** se usa vLex ni búsqueda por Google Chrome dentro del plugin.
- Lefebvre (El Derecho) y el vLex gratuito del colegio son herramientas externas propias de Gerardo, **no** cableadas al plugin.

---

## Estilo de la casa

| Campo | Valor |
|---|---|
| Voz redaccional | Pluma de Gerardo (`estilo-gerardo-escritos-judiciales`) — calibrar con escritos reales de Gerardo cuando se aporten muestras |
| Entregable | Word `.docx` maquetado para LexNET |
| Postura MASC por defecto | Burofax = MASC (art. 5 LO 1/2025) — DEFAULT, ajustar |

---

## Honorarios / encargo

| Campo | Valor |
|---|---|
| IBAN del despacho | [PENDIENTE — indicar el IBAN real de Gerardo] |
| Hoja de encargo | `/hoja-encargo` |

---

## Qué quiere implementar con Claude (prioridades de Gerardo)

1. Redactar demandas, contestaciones y recursos (todas las jurisdicciones).
2. Búsqueda de jurisprudencia (vía conector Jurisprudenciator).
3. Redacción de escritos jurídicos fundamentados.
4. Análisis de estrategia procesal de cada asunto, como un compañero del despacho con visión crítica y opiniones fundamentadas en Derecho.
5. Informes jurídicos de los asuntos.
6. (A valorar más adelante) contestar correos y clasificar documentación.

### Dónde se le va el tiempo (lo que el plugin debe aliviar)
Análisis de estrategia del asunto · recopilar doctrina y jurisprudencia aplicable · redacción de escritos fundamentados (demandas, contestaciones, recursos de apelación y reforma) releyendo todo el expediente.

---

## Apetito al riesgo y RC profesional

> Todo PENDIENTE — definir con `/customize` (cobertura RC, franquicia, bandas de severidad, escalera de autoridad para transigir).

---

## Colaboradores clave

> PENDIENTE — procurador de cabecera, peritos, colaboradores penal/laboral, mediador MASC. Completar con `/customize`.

---

## Historial de cambios

| Fecha | Acción |
|---|---|
| 2026-06-29 | Perfil inicial generado desde el Formulario de Diagnóstico de Gerardo Saucedo |
