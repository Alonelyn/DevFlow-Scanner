# DevFlow Scanner 2.0.1 — 12 de noviembre de 2026

Parche de estabilidad y usabilidad del motor universal.

- Selecciona el puerto real del backend y excluye el puerto interno de DevFlow.
- Advierte errores de escritura en la URL antes de confundirlos con fallos de permisos.
- Mantiene la sesión al ocultar y volver a abrir el panel.
- Formatea el cuerpo JSON del Laboratorio HTTP.
- Detecta cambios cada cinco segundos sin recargar la interfaz y ofrece aplicarlos manualmente.
- Incorpora `Quitar del historial` en el menú contextual de rutas recientes; nunca elimina la carpeta del equipo.

Validación: 33/33 pruebas del motor, análisis real de Basic Auth, JWT, NEXUM y PHP, más prueba de activación y reapertura dentro de VS Code.

## DevFlow Scanner 1.5.4 — 12 de noviembre de 2026

Actualización gratuita de consistencia para Visual Studio Code.

## Buscador avanzado para todos

- El buscador avanzado se habilita en cualquier proyecto que tenga al menos un endpoint.
- Los proyectos pequeños también pueden filtrar por método HTTP, ruta, controller, capa o rol.
- La navegación por teclado y la agrupación por controller están disponibles sin depender de la cantidad de endpoints.

## Correcciones conservadas

- El buscador permanece por encima de Spring Security, tablas y cartillas de arquitectura.
- El listado usa scroll interno y mantiene visibles sus filtros y atajos.
- El ícono lateral abre directamente DevFlow y libera la barra lateral.

## Verificación

- Se comprobó el buscador con NEXUM: 338 archivos y 148 endpoints.
- La prueba automática verificó el acceso lateral directo, el motor, el panel y el workspace.
- Windows x64 fue probado localmente; macOS Intel y Apple Silicon son compilaciones cruzadas preliminares.
## DevFlow Scanner 2.0.0

- Motor universal TypeScript/Node.js: ya no requiere .NET.
- Un único VSIX para Windows x64, macOS Intel y macOS Apple Silicon.
- Conserva análisis Java/Spring, Spring Security, JPA, frontend, PHP, GitHub, Board y Laboratorio HTTP.
- Validación automática en VS Code real sobre las tres plataformas antes de publicar.
- Paquete reducido de más de 100 MB a menos de 1 MB.
