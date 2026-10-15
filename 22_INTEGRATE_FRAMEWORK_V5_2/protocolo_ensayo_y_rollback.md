# Protocolo de staging y rollback
1. Verificar main = `5cba645d6a462801e40eb09b35108482aca58ed4`.
2. Mantener la rama de respaldo apuntando al mismo SHA de origen.
3. Incorporar *aditivamente* el paquete G2-R2 y sus extensiones, usando los nombres y hashes definidos en `manifest_payload_esperado.json`; no modificar el esquema Framework ni el árbol histórico.
4. Verificar SHA256 de cada archivo recibido y ausencia de fusiones de identidades CAT/FIC/MAT/CUR.
5. Ejecutar la importación/exportación nativa y recuperar sidecars con un procedimiento independiente, en un entorno de pruebas.
6. Comparar el árbol de staging contra main: ninguna ruta anterior puede ser suprimida o alterada.
7. Registrar pruebas y diferencias. Si fallan, detenerse; dejar main y respaldo intactos y nunca forzar el ref.
8. Solo con nuevo GO humano considerar PR/fusión posterior; este ensayo no autoriza ninguno.
## Evidencia pendiente
El resumen del Mac indica ocho etapas PASS y preservación, pero falta el informe JSON completo para su inspección en staging.
## Invariantes
Origen preservado, sidecars vinculados y no absorbidos por contrato nativo; decisiones humanas no inventadas; N3/N4 son valores declarados, no acreditaciones automáticas.
