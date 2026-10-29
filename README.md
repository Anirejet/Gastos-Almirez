# Gastos del hogar (app del móvil)

App web instalable (PWA) para apuntar gastos desde el móvil. Los datos no están en este repositorio:
viven en la hoja de Google del hogar y la app habla con ella a través de un servidor de Google Apps Script
protegido con una clave que se guarda solo en cada móvil.

Archivos:

- `index.html`: toda la app (pantallas, estilos y lógica).
- `sw.js`: service worker; hace que la app abra al instante y funcione sin conexión.
- `manifest.webmanifest` e iconos: permiten instalarla en la pantalla de inicio.

Para publicar una versión nueva basta con subir los archivos cambiados; los móviles la reciben solos
(a la segunda vez que se abre la app, o con Ajustes > Buscar actualización).
