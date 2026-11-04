# DevFlow Scanner 1.4.7 — 4 de noviembre de 2026

Actualización gratuita de la extensión para Visual Studio Code.

- Corrige la pantalla azul vacía del panel en versiones recientes de VS Code/Electron.
- Autoriza correctamente el ancestro interno `vscode-file:` requerido por el webview.
- El motor continúa limitado a `127.0.0.1`; no se habilita acceso desde la red local.
- Conserva todas las funciones de DevFlow Scanner 1.4.6 descritas a continuación.

- Añade un Laboratorio HTTP amplio con Bearer JWT, cabeceras y cuerpo JSON.
- Detecta tokens devueltos por un login y permite activarlos rápidamente para probar endpoints protegidos.
- Permite recordar perfiles JWT opcionales mediante SecretStorage de Visual Studio Code.
- Mejora **Flujo visual** con zoom, encuadre, tablas y notas movibles, conectores y código enfocado por endpoint.
- Elimina la pared invisible del Board: las tablas y notas pueden moverse en todas las direcciones.
- Añade Arquitectura plegable y un recorrido persistente con iluminación, sin mover automáticamente la pantalla.
- Las tarjetas de Arquitectura ajustan rutas largas y aumentan su altura sin cortar el contenido.
- Las notas conservan colores rápidos y añaden una paleta personalizada.
- Conserva el acceso al Explorador, rutas separadas, temas, actualización desde GitHub y línea de tiempo.
- Motor privado limitado a `127.0.0.1` y laboratorio HTTP limitado a localhost.
- Firma: Michael Castillo, UTP.
- Agradecimiento al docente: Johan Max Alexander Lopez Heredia.

Windows x64 superó la prueba automática de comando, motor, panel y workspace. Las versiones de macOS se publican como preliminares hasta validarlas en una Mac real.
