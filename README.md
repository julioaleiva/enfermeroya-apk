# EnfermeroYa para Android

Entrega v2026.11.25: Administración 0.1.7 (código 8); Enfermero y Paciente conservan 0.1.6 (código 7), sin cambios en sus APK.

## Descargas

- [Ad.Enf.YA! — Administración](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-admin.apk)
- [Pac.Enf.YA! — Paciente](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-paciente.apk)
- [Enf.Enf.YA! — Enfermero](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-enfermero.apk)
- [Notas de la entrega](https://github.com/julioaleiva/enfermeroya-apk/releases/tag/v2026.11.25)

Los APK locales están en archivos/ y se distribuyen como adjuntos de Releases; no se agregan al historial Git. Se conservan las releases anteriores.

Administración mejora el desplazamiento del listado de enfermeros y agrega acciones identificadas para activar, desactivar y archivar de forma recuperable. No aprueba legajos ni salda deudas automáticamente. La recuperación mantiene la cuenta inactiva. Las restricciones y la auditoría se aplican en servidor; migración de Supabase aplicada y verificada con autorización.

104 tests, tipos y 57 comprobaciones MVP aprobados. Pruebas aisladas en web y emulador con horizontal, fuente 200 % y teclado. Pendiente teléfono físico y concurrencia con conexiones PostgreSQL reales. Incluyen JavaScript para abrir sin Metro; las funciones conectadas requieren Internet.

Se conservan nombres, paquetes y firma histórica de pruebas Expo, no de Google Play. Presentación: versión y fecha/hora, sin código ni ART visibles. Los metadatos de cada artefacto están en version.json y sus huellas en SHA256SUMS.txt.

Código: https://github.com/julioaleiva/EnfermeroYa/commit/0149cc53623179a17b3e2876eaea707573b1be5c
