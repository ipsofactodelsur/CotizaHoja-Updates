# CotizaHoja — actualizaciones

Este repositorio **sólo publica los instaladores** de CotizaHoja, un cotizador
local de impresiones para Windows. El código fuente es privado.

## Instalar en un equipo nuevo

1. Descarga el instalador más reciente desde
   [la última versión](../../releases/latest).
2. Ejecútalo **como administrador** (Windows pedirá permiso).
3. Se instala en `C:\CotizaHoja` y configura la impresora virtual
   «Cotizador Test».

No hace falta cuenta de GitHub, ni iniciar sesión, ni instalar herramientas
adicionales.

## Actualizaciones

La aplicación comprueba este repositorio al iniciar y una vez al día. Si hay
una versión nueva:

1. Descarga el instalador.
2. Verifica su SHA-256 contra el archivo `version.json` de la versión.
3. Lo instala en silencio, conservando tarifas, papeles, costos y cotizaciones.

Windows mostrará el aviso de Control de cuentas de usuario porque la instalación
requiere permisos de administrador.

## Archivos de cada versión

| Archivo | Contenido |
| --- | --- |
| `CotizaHoja-Setup-X.Y.Z.exe` | Instalador completo |
| `version.json` | Versión, nombre del instalador, SHA-256 y notas |
| `checksums.txt` | Hash SHA-256 para verificación manual |
