# DevFlow Scanner 2.0.3 — 19 de noviembre de 2026

Parche de actualización automática y continuidad de sesión.

- Detecta cambios del backend o frontend cada cinco segundos y ejecuta un nuevo análisis en memoria.
- Actualiza endpoints, componentes, reglas Spring Security y roles sin pulsar **Analizar arquitectura**.
- Conserva URL, JSON, cabeceras, autenticación, pestaña activa y desplazamiento del Laboratorio.
- Conserva un botón de reintento manual si un archivo se encuentra incompleto mientras se escribe.
- Retira la referencia institucional de la licencia y mantiene la autoría personal.

Validación: cambio real de `SecurityConfig.java`, incorporación automática de SUPPORT en GET y nueva regla PUT, pruebas de backend, UI, sintaxis y empaquetado universal.

## DevFlow Scanner 2.0.2 — 14 de noviembre de 2026

Actualización oficial del Laboratorio HTTP enfocada en aprendizaje y diagnóstico.

- Añade **Backend Workspace** como vista opcional y conserva la vista clásica.
- Agrupa y filtra endpoints detectados por controller y método.
- Mantiene JWT, Basic Auth, cabeceras, ejemplos y explicaciones HTTP existentes.
- Integra CodeMirror para editar y formatear JSON con mayor claridad.
- Detecta preventivamente rutas parecidas ante letras omitidas, adicionales o sustituidas.
- Sugiere el endpoint correcto sin depender de nombres fijos como `clientes`.
- Corrige `Cannot read properties of null (reading 'method')` cuando la URL no coincide con el análisis.

Validación: pruebas de HTTP, seguridad, redacción, DTO, JPA, frontend, Spring Security, activación del host y empaquetado universal.

## DevFlow Scanner 2.0.1 — 12 de noviembre de 2026

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
