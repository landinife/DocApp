# SaludApp

App web de salud familiar: tomas de medicamentos, calendario de vacunación, turnos, controles e historia clínica.

- `index.html`: toda la app (HTML, CSS y JavaScript en un solo archivo).
- `manifest.webmanifest`, `icon-*.png`, `icon.svg`: ícono e instalación en el teléfono.

Estado: versión web con inicio de sesión con Google y sincronización en Firebase (proyecto `fliaapp`). Los datos se guardan dentro del hogar compartido, en colecciones con prefijo `doc_`. Los turnos se pueden traer del calendario "Salud" de Google Calendar. Los adjuntos de la historia se suben a Google Drive, a la carpeta de cada persona.
