# L1-A Criterios de Deduplicación v0.3

**Proyecto:** Proyecto_RIB_EG_IA  
**Versión:** v0.3  
**Fecha:** 2026-05-07  
**Estado:** Borrador operativo inicial

---

## Propósito

Evitar que una misma fuente aparezca como varias entradas independientes sin necesidad.

## Criterios

| Tipo de coincidencia | Acción |
|---|---|
| Mismo autor, año y título | Unificar como duplicado exacto |
| Mismo texto, distinta edición | Mantener como versión relacionada |
| Mismo recurso, distinto idioma | Vincular como traducción |
| Herramienta viva con cambio de nombre | Mantener historial de nombre |
| Fuente incompleta pero probable duplicado | Marcar como posible duplicado |

## Estados

- `duplicado_exacto`
- `version_relacionada`
- `traduccion`
- `herramienta_misma_linea`
- `posible_duplicado`
- `no_duplicado`
