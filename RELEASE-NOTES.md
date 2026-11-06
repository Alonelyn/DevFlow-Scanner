# DevFlow Scanner 1.4.10 — 6 de noviembre de 2026

Actualización gratuita de la extensión para Visual Studio Code.

- Detecta IDs JPA autogenerados mediante `@GeneratedValue`.
- Excluye campos generados por la base de datos de los ejemplos JSON de POST, PUT y PATCH.
- Muestra esos campos como autogenerados en la guía del cuerpo y no los considera obligatorios.
- Activa la publicación automática en Marketplace al publicar una GitHub Release con los tres paquetes.

- Añade HTTP Basic y cabeceras personalizadas al Laboratorio HTTP.
- Permite probar autenticación y autorización de Spring Security sin guardar contraseñas en el historial.
- Detecta reglas por estructura de código, sin depender de nombres como `SecurityConfig.java`.
- Reconoce `requestMatchers`, `anyRequest`, roles, autoridades, JWT/OAuth2, filtros, `STATELESS`, CSRF y anotaciones de seguridad.
- Muestra mecanismo, requisito, ruta, archivo, línea, evidencia y nivel de certeza en Arquitectura.

- Añade distribución automática, cómoda y compacta según el espacio real disponible en VS Code.
- Corrige desbordamientos horizontales en Arquitectura, Flujo visual y resoluciones pequeñas como 1366×768.
- Reorganiza los controles de Arquitectura y coloca Línea de tiempo antes del Laboratorio HTTP.
- Detecta el DTO utilizado por `@RequestBody`, sus campos y validaciones Spring.
- Genera un ejemplo JSON específico para el endpoint seleccionado mediante **Usar ejemplo**.
- Reconoce reglas como `@NotNull`, `@NotBlank`, `@NotEmpty`, `@Email`, `@Size`, `@Min`, `@Max` y `@Pattern`.
- Explica errores HTTP comunes y propone correcciones para 400, 401, 403, 404, 409, 415, 422 y 500.
- Conserva el Laboratorio HTTP con autorización Bearer JWT, captura del token de login y perfiles protegidos con SecretStorage.
- Conserva el Board interactivo, notas, temas, rutas separadas y actualización desde GitHub.
- El motor y las solicitudes del Laboratorio continúan limitados a `localhost`/`127.0.0.1`.
- Firma: Michael Castillo, UTP.
- Agradecimiento al docente: Johan Max Alexander Lopez Heredia.

## Verificación

- Windows x64 superó la prueba automática de comando, motor, panel y workspace.
- La cabecera `Authorization: Bearer …` fue verificada de extremo a extremo contra un backend local temporal.
- El token no se almacena ni se muestra en la línea de tiempo.
- El proyecto NEXUM fue analizado con 338 archivos y 148 endpoints; `POST /api/actividades` se relacionó correctamente con `ActividadRequest` y sus reglas.
- Las compilaciones de macOS se publican como preliminares hasta validarlas en una Mac real.
