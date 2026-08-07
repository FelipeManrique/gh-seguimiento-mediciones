# gh-seguimiento-mediciones

Dashboard de seguimiento de mediciones de GH Consultora, publicado con GitHub Pages.

**Estado:** en construcción. El shell público no contiene datos de mediciones — esos
solo se sirven a cuentas de Google autorizadas a través de un backend en Google Apps
Script.

## Estructura

- `index.html` — shell público (sin datos sensibles).
- Login con Google + fetch a un Web App de Apps Script que valida el email contra
  una lista autorizada antes de devolver datos.

## Fuente de datos

- Planilla `Seguimiento de monitoreos - Datos` (pestaña anual + pestaña "Checklist
  proceso" para el seguimiento del proceso).
- Cruce en vivo con la planilla `CALIBRACIONES_DATA` del dashboard de calibraciones
  para el estado de los equipos.
