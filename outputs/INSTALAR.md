Reto en Casa: publicar e instalar

Esta carpeta contiene la app web instalable (PWA): retoencasa.html, manifest.webmanifest, sw.js e icon.svg.

Publicación necesaria

Para instalar desde un teléfono, los archivos deben estar juntos en una dirección HTTPS pública. El protocolo file:// no permite instalar una PWA ni habilitar cámara en la mayoría de los navegadores. Sube el contenido de esta carpeta a un alojamiento estático HTTPS como GitHub Pages, Netlify o Cloudflare Pages; luego abre la dirección HTTPS en el teléfono.

- Android: en Chrome, abre la página y toca Instalar app (o Añadir a pantalla de inicio).
- iPhone: abre la página en Safari, toca Compartir y Añadir a pantalla de inicio.
- Sin conexión: después de abrirla una vez mientras haya internet, la app puede volver a abrirse sin conexión. Los datos permanecen en el almacenamiento local de ese navegador y dispositivo.

La app actual es local y no sincroniza partidas/chat entre teléfonos. Las partidas en línea necesitan un servicio de salas y cuentas.
