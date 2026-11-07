# EnfermeroYa para Android

Aplicaciones Administración, Paciente y Enfermero. Versión 0.1.4, código 5, publicada el 07/11/2026.

## Descargas

- [Ad.Enf.YA! — Administración](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-admin.apk)
- [Pac.Enf.YA! — Paciente](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-paciente.apk)
- [Enf.Enf.YA! — Enfermero](https://github.com/julioaleiva/enfermeroya-apk/releases/latest/download/enfermeroya-enfermero.apk)
- [Release y notas completas](https://github.com/julioaleiva/enfermeroya-apk/releases/tag/v2026.11.07.2)

Los APK se conservan localmente en archivos/ y se publican como adjuntos de GitHub Releases. No se agregan como binarios al historial de Git.

Incluyen JavaScript y abren sin Metro. Las funciones conectadas requieren Internet. Se conserva la firma de pruebas Expo para actualizar instalaciones anteriores; no es una firma para Google Play.

## Novedades

Encabezado homogéneo en las tres apps: logo y datos de compilación alineados. Se quitaron los saludos superiores y rótulos de rol; Perfil sigue disponible en la barra inferior. Texto con altura natural para evitar recortes, también con letras ampliadas.

En 0.1.4 las tres apps muestran versión, compilación y fecha ART incorporada al compilar. Se conservan los nombres Ad.Enf.YA!, Enf.Enf.YA! y Pac.Enf.YA!, los paquetes y la firma. Los datos persisten al reiniciar y sin conexión. La memoria documenta el procedimiento para futuras compilaciones.

Mejoras visuales y táctiles en las tres apps. Administración permite habilitación excepcional por deuda y búsqueda por nombre o correo en Arqueo. Paciente recupera y muestra avisos internos de aceptación sin reiniciar. El legajo permite una foto de perfil opcional, separada de los documentos obligatorios.

Los avisos son internos; push con la app cerrada queda pendiente. Las webs pueden tener una versión distinta mientras no se actualicen.

## Verificación

88 tests, tipos y 57 comprobaciones MVP aprobados. Se verificaron los tres APK: versión/código, nombres, paquetes, firma, JavaScript, entorno y coincidencia del JSON con el bundle. Revisión de encabezados en web y emuladores Android con texto ampliado y reinicio offline; regeneración comprobada ante una segunda compilación. Falta prueba manual en teléfono físico.

Las huellas SHA-256 están en SHA256SUMS.txt y los datos de versión en version.json. El certificado SHA-256 es fac61745dc0903786fb9ede62a962b399f7348f0bb6f899b8332667591033b9c.

Código de esta versión: https://github.com/julioaleiva/EnfermeroYa/commit/877c2001d92e014382ca6c030c02209b1210ab75

Desarrollado por WSS W Systems And Solutions. Contacto: wssarg@gmail.com.