# DevFlow Scanner 1.5.3 — 12 de noviembre de 2026

Parche gratuito de experiencia de uso para Visual Studio Code.

## Correcciones

- El buscador compacto de endpoints permanece por encima de Spring Security, tablas y cartillas de arquitectura.
- El menú conserva su altura, filtros y navegación sin quedar oculto por secciones posteriores.
- Pulsar el ícono de DevFlow en la barra lateral abre directamente el scanner en el editor.
- La barra lateral se cierra después de abrir DevFlow para devolver el espacio al proyecto.
- Se conservan el acceso desde la barra de estado y los comandos de la paleta.

## Verificación

- Se analizó NEXUM con 338 archivos y 148 endpoints.
- El buscador fue abierto sobre 65 reglas de Spring Security y permaneció en primer plano.
- La prueba automática verificó el acceso lateral directo, el motor, el panel y el workspace.
- Windows x64 fue probado localmente; los paquetes de macOS continúan como compilaciones cruzadas preliminares.
