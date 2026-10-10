# DocApp

App web de salud familiar: tomas de medicamentos, calendario de vacunación, turnos, controles e historia clínica.

- `index.html`: toda la app (HTML, CSS y JavaScript en un solo archivo).
- `manifest.webmanifest`, `icon-*.png`, `icon.svg`: ícono e instalación en el teléfono.

Estado: versión web con inicio de sesión con Google y sincronización en Firebase (proyecto `fliaapp`). Los datos se guardan dentro del hogar compartido, en colecciones con prefijo `doc_`. Pendiente: lectura del calendario "Salud" de Google Calendar y carpeta de estudios en Google Drive.
