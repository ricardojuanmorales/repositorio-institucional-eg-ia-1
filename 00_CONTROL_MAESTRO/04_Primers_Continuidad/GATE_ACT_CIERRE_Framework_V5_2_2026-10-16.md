# GATE ACT-01 · Cierre verificable de activación mínima RIB-EG-IA
**Fecha:** 2026-10-16  
**Tipo:** gate único de aceptación/continuidad; no sustituye al contrato del Framework ni a la aprobación humana.
**Autoridad:** Ricardo Juan Morales De Jesús, Ph.D.  
**Ámbito:** RIB-EG-IA, modo INTEGRATE, Framework Genérico v5.2.0.
## Criterios verificables
| ID | Verificación | Evidencia | Estado |
|---|---|---|---|
| G-01 | 22 cartapacios oficiales `00–21` y `99_ARCHIVO_HISTORICO` existen, más `22_INTEGRATE_FRAMEWORK_V5_2` propio del proyecto | Árbol `main` GitHub | PASS (raíz, no identidad de contenidos con Framework maestro) |
| G-02 | Patrimonio CAT/FIC/MAT/CUR y originales preservados; sin fusiones automáticas | Paquete G2-R2 y cierre INTEGRATE; respaldo histórico | PASS documentado |
| G-03 | Modo INTEGRATE, frameworkVersion 5.2.0, niveles y perfiles compatibles con esquema | `22_INTEGRATE_FRAMEWORK_V5_2/Activacion_Framework_V5_2/project-package-activado.json` | PASS documental; ejecutar importación nativa al reabrir para prueba funcional actual |
| G-04 | START/INTEGRATE declarados distintos con contrato común; activación mínima compatible | Contrato V5 candidato + ficha `Activacion_Minima_RIB_EGIA_V5_2_2026-10-16.md` | PASS conceptual |
| G-05 | README usuario ilustrado actualiza estado, estructura, documentación y ruta de inicio | `README.md` | Verificar en cierre |
| G-06 | Entrega local reproducible sin sobrescribir trabajo local | ZIP cierre + instrucciones `git pull --ff-only` y verificación | PENDIENTE ejecución por titular en Mac |
| G-07 | No se afirma certificación N4, despliegue ni equivalencia app/experto | Esta acta y README | PASS delimitación |
| G-08 | Deuda profunda N3/N4, Marco Mundi, TSR, anexos dialógicos y laboratorio vivo explícita | Este gate | PASS registro |
## Decisión de gate
**Resultado previsto:** GO condicionado al cierre de sincronización local (G-06) y a la confirmación final G-05. La documentación mínima se considera cerrada; no autorizar despliegue, revisión destructiva, cambios al Framework maestro ni publicación en WordPress.
**Regla:** si el estado local difiere de `main`, detener el avance y conservar ambas copias; nunca forzar `git reset --hard` ni `git push --force`.
## Deuda diferida, no bloqueante
Profundización estratégica/sistémica/holística/transdisciplinaria N3/N4; ratificación propia de Marco Mundi; demostración de equivalencia aplicación↔experto; preservación de anexos desconocidos en ZIP roundtrip; transferencia simétrica reversible técnica, semántica y pedagógica; evaluación longitudinal; SDD local-first y CI/CD de laboratorio vivo inspirado en AI StoryLab 1 y Materia Mundi. No crear documentos nuevos por cada deuda.
## Al reabrir
Verificar G-06, actualizar esta casilla y trabajar directamente en un bloque académico. Una única decisión humana al siguiente cambio material.
