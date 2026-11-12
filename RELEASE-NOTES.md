# DevFlow Scanner 1.5.2 — 12 de noviembre de 2026

Actualización gratuita de la extensión para Visual Studio Code.

## Buscador compacto de endpoints

- Filtra por método HTTP, ruta, controller, capa o rol sin ocupar una segunda fila permanente.
- Agrupa los resultados por controller y permite navegar con las flechas, seleccionar con Enter y cerrar con Escape.
- Conserva la iluminación del recorrido cuando el usuario filtra o cambia de endpoint.
- Mejora el espaciado tipográfico y la adaptación a distintos anchos de VS Code.

## Laboratorio HTTP y experiencia visual

- Añade estados de carga y una capa de animaciones opcional que no bloquea la interfaz.
- Refuerza los diagnósticos educativos de solicitudes correctas, credenciales rechazadas y rutas inexistentes.
- Mantiene visible la respuesta JSON real para preparar al alumno para entornos profesionales.

## Verificación

- NEXUM fue analizado con 338 archivos y 148 endpoints; se verificaron filtros por rol y método.
- El recorrido iluminado permaneció activo al cambiar el endpoint desde el buscador.
- El Laboratorio fue probado con respuestas HTTP 200, 401 y 404.
- Windows x64 superó la prueba automática de comando, motor, panel y workspace.
- Las compilaciones de macOS se publican como preliminares hasta validarlas en una Mac real.
