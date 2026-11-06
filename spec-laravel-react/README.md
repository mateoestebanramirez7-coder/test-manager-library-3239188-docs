# Spec Laravel + React — Manager Library

Traducción del spec `spec-.net/` al stack del reto (React y PHP con Laravel). El negocio (historias, criterios de aceptación, reglas, contrato de la API y modelo de datos) se respeta tal cual; solo cambian las decisiones de tecnología. Prueba técnica SDD · Ficha ADSO 3239188.

Los documentos viven en el repo `api` de este fork, para no duplicarlos:

| Documento | Qué contiene |
|---|---|
| [`SPEC-NOTES.md`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/blob/main/SPEC-NOTES.md) | Traducción, supuestos, trazabilidad HU → endpoint → tarea, estado y riesgos |
| [`plan.md`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/blob/main/plan.md) | Plan técnico traducido (D-01 a D-14) |
| [`architecture.md`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/blob/main/architecture.md) | Capas del backend, flujo de prestar, errores y diseño del frontend |
| [`tasks.md`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/blob/main/tasks.md) | Tareas T-01 a T-23 con evidencia y estado |
| [`test-cases.md`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/blob/main/test-cases.md) | Un caso de prueba por criterio de aceptación |
| [`adr/`](https://github.com/mateoestebanramirez7-coder/test-manager-library-3239188-api/tree/main/adr) | ADR-005 a ADR-007 (los ADR 001 a 004 son los del spec original) |

## Qué se tomó del spec original

Se leyó `spec-.net/` completo. `spec-python/` no se revisó porque el README de este repo confirma que describe el mismo producto.

## Estado

Entrega de diseño y documentación. La implementación está pendiente; el estado real de cada tarea está en `SPEC-NOTES.md` y `tasks.md`.