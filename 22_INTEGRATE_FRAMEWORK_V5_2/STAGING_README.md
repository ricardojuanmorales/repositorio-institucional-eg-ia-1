# RIB-EG-IA · staging INTEGRATE Framework v5.2
Estado: ensayo aislado, **NO es integración en main**.
Base inmutable main: `5cba645d6a462801e40eb09b35108482aca58ed4`.
Rama de respaldo: `backup/pre-integrate-v0.3-20261015`.
Autorización humana: preparar y ensayar staging, sin fusión, PR ni publicación.
Configuración: lentes IT/PH/AT activos, projectLevel N3, autonomyLevel N4, mode INTEGRATE, preservationRule preserve_source.
La autonomía N4 es declarativa y no autoriza acciones autónomas sin control humano.
Preservar CAT/FIC/MAT/CUR por separado; ninguna identidad bibliográfica incierta puede fusionarse automáticamente.
Los originales existentes en main permanecen intactos.
**Estado del payload**: los nueve archivos están cargados en staging. Se verificaron tamaños y SHA Git de sus blobs contra copias locales cuyos SHA-256 coinciden con el manifiesto. Los 189 archivos históricos permanecen intactos. Esto acredita integridad y staging aditivo, no prueba aún la importación operativa íntegra desde GitHub.
**Validación G3**: salida del Mac declara PASS/8 y preserved=true. El JSON de evidencia completo debe adjuntarse para auditoría. No afirmar suite funcional inspeccionada sin dicho reporte.
Se reserva a la autoridad humana la decisión de fusionar a main.
