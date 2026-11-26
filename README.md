# EnfermeroYa para Android

Entrega v2026.11.25.1: Administración y Enfermero 0.1.8 (código 9). Paciente conserva exactamente su APK 0.1.6 (código 7).

## Descargas

- [Ad.Enf.YA! — Administración](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-admin.apk)
- [Pac.Enf.YA! — Paciente](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-paciente.apk)
- [Enf.Enf.YA! — Enfermero](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-enfermero.apk)
- [Notas de la entrega](https://github.com/julioaleiva/enfermeroya-apk/releases/tag/v2026.11.25.1)

Los APK locales están en archivos/ y se distribuyen como adjuntos de Releases; no se agregan al historial Git. Se conservan las releases anteriores.

Se ocultan los códigos internos en las vistas habituales de Administración y Enfermero. Las referencias de soporte quedan bajo «Ver referencias técnicas»; auditoría, exportaciones y confirmación de reinicio conservan sus identificadores. Este ajuste no modifica Supabase ni reglas de negocio.

Administración mejora el desplazamiento del listado de enfermeros y agrega acciones identificadas para activar, desactivar y archivar de forma recuperable. No aprueba legajos ni salda deudas automáticamente. La recuperación mantiene la cuenta inactiva. Las restricciones y la auditoría se aplican en servidor; migración de Supabase aplicada y verificada con autorización.

104 tests, tipos y 57 comprobaciones MVP aprobados. Pruebas aisladas en web y emulador con horizontal, fuente 200 % y teclado. Pendiente teléfono físico y concurrencia con conexiones PostgreSQL reales. Incluyen JavaScript para abrir sin Metro; las funciones conectadas requieren Internet.

Se conservan nombres, paquetes y firma histórica de pruebas Expo, no de Google Play. Presentación: versión y fecha/hora, sin código ni ART visibles. Los metadatos de cada artefacto están en version.json y sus huellas en SHA256SUMS.txt.

Código: https://github.com/julioaleiva/EnfermeroYa/commit/93c20ecabb111803d580969a660d8cfa424c8313

