# Litigacion civil Espana - conectores

Plugin de litigacion civil, mercantil y de familia para Espana (LO 1/2025, LEC, EGA),
conectado de fabrica al conector Jurisprudenciator.

## Conector

- **Jurisprudenciator** (MCP remoto) - **unica** via de busqueda y verificacion de
  jurisprudencia espanola. Resuelve el captcha/antidescargas del CENDOJ en el servidor
  y cubre TS, AN, AP, TSJ y juzgados (civil, penal, contencioso, social, militar).
  Endpoint: `https://mcp.jurisprudenciator.lexiaipro.org/mcp`
  Tools: `buscar_sentencias`, `buscar_por_cita`, `leer_sentencias`, `opciones_busqueda`,
  `resolver_captcha`, `estado`.

Al instalar el plugin solo hay que activar el conector en el chat/proyecto. No se busca
jurisprudencia por vLex ni por Google Chrome: todo va por Jurisprudenciator.

## Skills

Incluye las skills de cartera de asuntos y redaccion de escritos: intake y briefing de
asuntos, demandas, contestaciones, recursos de apelacion y reposicion, ejecucion, medidas
cautelares, MASC, cronologias, cuadros de elementos, interrogatorios, tasaciones de costas,
burofax, hoja de encargo y mas. La busqueda y verificacion de jurisprudencia (ECLI/ROJ) se
hace siempre con el conector Jurisprudenciator.
