# DevFlow Scanner para VS Code

Extensión visual educativa para comprender el recorrido de la información entre:

`Frontend → Controller → Service → Repository → Model`

## Funciones

- Detección de proyectos y servidores locales.
- Mapa visual de arquitectura.
- Detección de llamadas frontend y endpoints Spring.
- Visualización del archivo fuente completo.
- Recorrido persistente de endpoints sin desplazar automáticamente la pantalla.
- Panel interactivo **Flujo visual** para iluminar y estudiar cada recorrido.
- Board con zoom, encuadre, tablas y notas movibles sin límites direccionales.
- Notas con colores rápidos y selector de cualquier color.
- Laboratorio HTTP con autorización Bearer JWT, cabeceras y cuerpo JSON.
- Autenticación HTTP Basic y editor de cabeceras personalizadas.
- Análisis educativo de reglas Spring Security, roles, mecanismos y evidencia del código.
- Detección de `@GeneratedValue` y exclusión de IDs autogenerados en los ejemplos de solicitud.
- Guía automática de DTO, campos requeridos, validaciones y ejemplos JSON para endpoints Spring.
- Explicaciones prácticas para errores HTTP comunes, incluidos 400, 401, 403, 404, 415 y 500.
- Laboratorio HTTP limitado a `localhost`.
- Línea de tiempo de solicitudes.
- Temas claro/oscuro y personalización de color.
- Detección automática de actualizaciones publicadas en GitHub.
- Modo privacidad reversible y rutas recientes plegables en el panel izquierdo.

## Vista rápida de DevFlow 1.4.11

### Arquitectura y Spring Security

![Arquitectura y reglas Spring Security](docs/images/arquitectura-seguridad.png)

### Modo privacidad y rutas recientes

![Modo privacidad y rutas recientes](docs/images/privacidad-recientes.png)

### Filtro para configuraciones con muchas reglas

![Reglas de seguridad filtradas](docs/images/seguridad-filtrada.png)

### Laboratorio HTTP

![Laboratorio HTTP](docs/images/laboratorio-http.png)

### Flujo visual y notas de aprendizaje

![Flujo visual y notas](docs/images/flujo-visual-board.png)

## Descarga

Descarga el archivo correspondiente desde la sección **Releases**:

- Windows x64: `DevFlow-Scanner-win32-x64-1.4.11.vsix`
- Mac Apple Silicon: `DevFlow-Scanner-darwin-arm64-1.4.11.vsix`
- Mac Intel: `DevFlow-Scanner-darwin-x64-1.4.11.vsix`

La versión Windows superó la prueba automática del paquete. Las compilaciones de macOS requieren validación final en una Mac real.

## Instalación

En VS Code abre **Extensiones → … → Instalar desde VSIX...** y selecciona el archivo descargado. Después ejecuta **DevFlow: Abrir Scanner** o pulsa **DevFlow** en la barra de estado. Para comprobar manualmente una versión nueva usa **DevFlow: Buscar actualizaciones en GitHub**.

Desarrollador: **Michael Castillo, UTP**

Agradecimiento al docente: **Johan Max Alexander Lopez Heredia**
