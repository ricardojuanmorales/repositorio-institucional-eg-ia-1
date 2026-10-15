# Proyecto RIB-EG-IA

**Repositorio Institucional de Colecciones Bibliográficas en Educación General e Inteligencia Artificial**

**Autor y responsable académico:** Ricardo Juan Morales De Jesús, Ph.D.  
**Adscripción:** Departamento de Ciencias Físicas, Facultad de Estudios Generales, Universidad de Puerto Rico en Río Piedras  
**Línea estructural de origen:** v0.3 (2026-05-07)  
**Último hito documentado:** INTEGRATE documental/técnico con Framework Genérico v5.2.0 (2026-10-15)  
**Estado:** artefactos integrados y versionados en GitHub; operación académica y publicación aún no desplegadas.

> La autoría académica indicada no implica aval, certificación o publicación oficial de la Universidad de Puerto Rico.

## Propósito

Organizar, preservar, relacionar y desarrollar colecciones bibliográficas para la enseñanza, la investigación y la creación transdisciplinaria en Estudios Generales, con apoyo de inteligencia artificial responsable, trazabilidad documental y revisión humana.

El proyecto conserva bibliografía generalizada y anotada, matrices, asignaciones curriculares, taxonomías, gobernanza, documentación activa y capacidades futuras de publicación. Se priorizan la agencia humana, la integridad de las fuentes y la distinción entre evidencia confirmada y propuestas pendientes.

## Estado verificable

La integración **documental y técnica** con Framework Genérico v5.2.0 fue aprobada y realizada mediante fusión *fast-forward* en `main` el **15 de octubre de 2026**.

| Aspecto | Resultado documentado |
|---|---|
| Integración GitHub | 12 archivos añadidos en `22_INTEGRATE_FRAMEWORK_V5_2/`; ningún archivo histórico modificado o eliminado durante la fusión |
| Framework | Contrato portable v5.2.0 y extensiones acompañantes, sin alterar los esquemas nativos |
| Pruebas del candidato | 8 etapas PASS; Vitest: 41/41 pruebas en 9 archivos, incluidas 8 pruebas específicas RIB-EG-IA |
| Patrimonio | Fuentes originales conservadas y correspondencias CAT/FIC/MAT/CUR registradas sin fusiones automáticas |
| Perfiles activos | IT, PH y AT |
| Nivel de proyecto | N3 |
| Nivel de autonomía | N4 **declarado**, no acreditación empírica automática |
| Modalidad | `INTEGRATE` / `preserve_source` |
| Publicación WordPress y aplicación web | **No desplegadas** |

**Commit de integración:** [`7b347d1799c763ded55b187cf493b608a39da540`](https://github.com/ricardojuanmorales/repositorio-institucional-eg-ia-1/commit/7b347d1799c763ded55b187cf493b608a39da540).  
**Cierre documental posterior:** consultar el [historial de `main`](https://github.com/ricardojuanmorales/repositorio-institucional-eg-ia-1/commits/main).  
**Respaldo previo:** [`backup/pre-integrate-v0.3-20261015`](https://github.com/ricardojuanmorales/repositorio-institucional-eg-ia-1/tree/backup/pre-integrate-v0.3-20261015), commit `5cba645d6a462801e40eb09b35108482aca58ed4`.

## Patrimonio bibliográfico y criterio de identidad

La evidencia inicial incluye:

- **CAT:** 60 entradas de catálogo.
- **FIC:** 60 fichas de bibliografía anotada desarrolladas.
- **MAT:** 60 relaciones o registros de matriz.
- **CUR:** 150 asignaciones curriculares en cinco unidades, **no necesariamente 150 obras únicas**.

Los identificadores históricos pueden designar obras distintas en conjuntos diferentes; por ejemplo, `BA-004` presenta una colisión CAT/FIC. Las equivalencias semánticas son candidatas de conciliación, no una autorización para deduplicar, reatribuir ni alterar documentos fuente. Las verificaciones bibliográficas, de derechos y procedencia siguen sujetas a curaduría.

## Arquitectura y documentación operativa

- [Paquete integrado Framework v5.2.0](22_INTEGRATE_FRAMEWORK_V5_2/) y [manifiesto del payload](22_INTEGRATE_FRAMEWORK_V5_2/manifest_payload_esperado.json).
- [Bitácora de cierre de sesión 004](00_CONTROL_MAESTRO/00_Bitacoras/Bitacora_Sesion_004_Cierre_INTEGRATE_Framework_V5_2_2026-10-15.md).
- [Primer actualizado de continuidad](00_CONTROL_MAESTRO/04_Primers_Continuidad/Primer_Cierre_INTEGRATE_Framework_V5_2_2026-10-15.md).
- [Registro de decisiones](00_CONTROL_MAESTRO/01_Decisiones/Registro_Decisiones_RIB_EGIA_v0_3.md).
- [Changelog](00_CONTROL_MAESTRO/02_Changelog/Changelog_General_RIB_EGIA.md) y [REL-002](00_CONTROL_MAESTRO/03_Releases/REL-002_INTEGRATE_Framework_V5_2_2026-10-15.md).

El informe ejecutivo histórico aprobado por el autor existe como documento editorial independiente. **No se presume publicado en este repositorio.** Los artefactos de integración no constituyen por sí mismos un servicio bibliográfico interactivo.

## Principios de gobernanza

1. El juicio académico humano gobierna las decisiones editoriales, bibliográficas y de publicación.
2. Se conserva la procedencia, la versión de origen y el derecho a revisión o reversión.
3. Los registros CAT/FIC/MAT/CUR mantienen identidad separada mientras exista incertidumbre.
4. Se distinguen **capacidad declarada**, **prueba técnica ejecutada** y **servicio efectivamente desplegado**.
5. La autonomía N4 es una configuración de trabajo gobernado, no permiso de operación desatendida.
6. Todo nuevo cambio material en `main` o publicación requiere autorización humana según su alcance.

## Entornos de trabajo

| Entorno | Función |
|---|---|
| Cartapacio local | Taller editable, custodia de originales y respaldo |
| GitHub | Versionado, documentación, trazabilidad y colaboración |
| Obsidian | Navegación y relaciones de conocimiento, cuando se configure |
| WordPress | Publicación institucional futura, aún no realizada |

## Estructura principal

- `00_CONTROL_MAESTRO/`
- `01_FUNDAMENTO_FILOSOFICO/`
- `02_ARQUITECTURA_CONCEPTUAL/`
- `03_METODOLOGIA_Y_FLUJO_DE_TRABAJO/`
- `04_GOBERNANZA_ETICA_Y_RIESGOS/`
- `05_COMPETENCIAS_Y_PERFILES/`
- `06_PASTILLAS_MODULARES/`
- `07_PLANTILLAS_Y_MODELOS/`
- `08_CURSOS_PROGRAMAS_Y_TRAYECTORIAS/`
- `09_IA_AGENTES_Y_COPILOTOS/`
- `10_REPOSITORIOS_Y_FLUJO_TECNICO/`
- `11_MULTIMODALIDAD_Y_PUBLICACION/`
- `12_DISENO_INSTRUCCIONAL_UNIVERSAL/`
- `13_INVESTIGACION_Y_EVIDENCIA/`
- `14_COMUNIDAD_TRANSFERENCIA_Y_ESCALAMIENTO/`
- `15_EVALUACION_CALIDAD_Y_AUDITORIA/`
- `16_SEGURIDAD_PRIVACIDAD_Y_DATOS/`
- `17_INTERNACIONALIZACION_LOCALIZACION/`
- `18_DOCUMENTACION_ACTIVA/`
- `19_IMPLEMENTACION_Y_DESPLIEGUE/`
- `20_MANTENIMIENTO_Y_EVOLUCION/`
- `21_WIKI_DOCUMENTACION_HUMANA/`
- `99_ARCHIVO_HISTORICO/`

## Próxima fase

La siguiente etapa es **operacionalizar el repositorio para uso académico**: acceso y consulta bibliográfica, curaduría de referencias y conflictos, revisión de derechos, criterios editoriales y preparación de publicación. No se requiere repetir los gates F0–G3 ya documentados.

Para reactivar el trabajo, leer primero el [primer de continuidad](00_CONTROL_MAESTRO/04_Primers_Continuidad/Primer_Cierre_INTEGRATE_Framework_V5_2_2026-10-15.md) y verificar el estado actual de `main`.

## Autoría y uso de IA

**Ricardo Juan Morales De Jesús, Ph.D.**  
Departamento de Ciencias Físicas, Facultad de Estudios Generales, Universidad de Puerto Rico en Río Piedras.

La IA se ha utilizado como apoyo para análisis técnico, organización, pruebas y redacción documental bajo revisión y decisión humana. La exactitud de las referencias, los derechos de uso y toda publicación institucional requieren validación responsable.

---

*Actualizado: 15 de octubre de 2026. Este README describe el estado documentado, no promete funcionalidades aún no habilitadas.*
