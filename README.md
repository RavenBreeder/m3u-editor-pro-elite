# 📺 M3U Editor Pro Elite

**Free, open-source M3U and IPTV playlist editor — no installation or account required.**

![Version](https://img.shields.io/badge/version-2.0-blueviolet) ![License](https://img.shields.io/badge/license-MIT-green) ![Platform](https://img.shields.io/badge/platform-Web-blue)

[Open in GitHub Pages](https://ravenbreeder.github.io/m3u-editor-pro-elite/) · [Blogger edition](https://m3ueditorpro.blogspot.com/) · [Download HTML](https://raw.githubusercontent.com/RavenBreeder/m3u-editor-pro-elite/main/index.html) · [Español](#español)

M3U Editor Pro Elite is a free, privacy-focused web application for editing, merging, cleaning and organizing IPTV playlists. It processes playlists directly in your browser, without requiring a dedicated backend, registration or subscription.

Created by independent developer **RavenBreeder**, the project has been available for free since **February 28, 2026**. Its goal is to make useful playlist management tools accessible to everyone.

## ✨ Features

- Import multiple M3U, M3U8 and TXT files; merge compatible playlists.
- Add, edit, delete, search and sort channels.
- Manage categories: rename, merge, delete and move channels in bulk.
- Remove duplicate stream URLs and normalize playlist formatting.
- Find and replace names, URLs, groups and TVG attributes in bulk.
- Export complete playlists, selected channels or categories.
- Preserve existing M3U metadata and additional directives; protect HLS manifests from destructive structural edits.
- Check HTTP link availability with cancellation and an explicit unknown status.
- Undo and redo changes, with a bounded history of up to 20 operations.
- Optional local backups using IndexedDB or localStorage, depending on browser support.
- Web Workers and pagination for large playlists; tested with synthetic lists of up to 100,000 channels in a controlled Chromium environment.
- Light, dark and system themes, compact mode and responsive layout.
- English and Spanish interface.
- Standalone HTML edition for offline playlist editing.

## 🔒 Privacy and security

Playlist editing takes place locally in your browser. The editor does not upload playlists to an application backend. Optional backups are stored in your browser and may contain credentials; enable them only on trusted devices.

Network features are different: HTTP checks contact the stream servers you choose to test, and the contact form sends the submitted information to Formspree. Avoid sharing private links, passwords or tokens. The hosted pages and external links are subject to their respective providers' privacy policies.

HTTP checks are not playback tests. A successful HTTP response does not guarantee a playable stream. CORS, redirects, timeouts and browser security restrictions may prevent verification. Unverifiable links are not automatically classified as dead.

## 🚀 Getting started

1. Open the [online editor](https://ravenbreeder.github.io/m3u-editor-pro-elite/).
2. Import your playlist file or paste its M3U content and load it.
3. Edit, organize, merge or clean the channels.
4. Export the resulting playlist and open it in your preferred compatible player.

For offline editing, save the [standalone index.html](https://raw.githubusercontent.com/RavenBreeder/m3u-editor-pro-elite/main/index.html) file and open it in a modern browser. Network features require an internet connection, and local-file storage support varies by browser.

## 🤝 Contributing

Suggestions, bug reports and contributions are welcome through [GitHub Issues](https://github.com/RavenBreeder/m3u-editor-pro-elite/issues). If you find the project useful, consider starring the repository. Please use synthetic or anonymized playlists when reporting bugs.

This is a playlist management tool, not an IPTV service. It does not provide channels or subscriptions. Use it with content you are authorized to access.

---

## Español

**Editor gratuito y de código abierto de listas M3U e IPTV, sin instalación ni registro obligatorio.**

[Usar en GitHub Pages](https://ravenbreeder.github.io/m3u-editor-pro-elite/) · [Edición Blogger](https://m3ueditorpro.blogspot.com/) · [Descargar HTML](https://raw.githubusercontent.com/RavenBreeder/m3u-editor-pro-elite/main/index.html)

M3U Editor Pro Elite permite editar, fusionar, limpiar y organizar listas IPTV directamente desde el navegador, sin necesidad de servidor propio, cuentas ni suscripciones.

Desarrollado de forma independiente por **RavenBreeder** y disponible gratuitamente desde el **28 de febrero de 2026**, su objetivo es ofrecer herramientas útiles y accesibles para todos.

### ✨ Funciones principales

- Importación múltiple de archivos M3U, M3U8 y TXT, y fusión de listas compatibles.
- Creación, edición, eliminación, búsqueda y ordenamiento de canales.
- Administración de categorías: renombrar, fusionar, eliminar y mover canales masivamente.
- Eliminación de URLs duplicadas y normalización del formato M3U.
- Búsqueda y reemplazo masivo de nombres, URLs, grupos y atributos TVG.
- Exportación completa, por selección o por categoría.
- Conservación de metadatos y directivas M3U existentes; protección de manifiestos HLS ante cambios estructurales destructivos.
- Verificación HTTP cancelable, con estado no verificable cuando no es posible confirmar una respuesta.
- Deshacer y rehacer, con historial limitado a un máximo de 20 operaciones.
- Respaldo local opcional mediante IndexedDB o localStorage, según el navegador.
- Web Workers y paginación para listas grandes; probado con listas sintéticas de hasta 100,000 canales en un entorno controlado de Chromium.
- Temas claro, oscuro y automático, modo compacto e interfaz adaptable.
- Disponible en español e inglés.
- Edición HTML independiente para editar listas sin conexión.

### 🔒 Privacidad y seguridad

La edición de las listas se realiza localmente en el navegador. El editor no sube las listas a un servidor de aplicación. Los respaldos opcionales se guardan en el navegador y pueden contener credenciales; actívalos únicamente en dispositivos de confianza.

Las funciones de red son diferentes: la verificación HTTP contacta con los servidores de los enlaces que decidas comprobar, y el formulario de contacto envía los datos introducidos a Formspree. No compartas enlaces privados, contraseñas ni tokens. Las páginas alojadas y los enlaces externos están sujetos a las políticas de sus respectivos proveedores.

La verificación HTTP no equivale a una prueba de reproducción. Una respuesta favorable no garantiza que el canal sea reproducible. CORS, redirecciones, tiempos de espera y restricciones del navegador pueden impedir la comprobación. Los enlaces no verificables no se clasifican automáticamente como caídos.

### 🚀 Cómo utilizarlo

1. Abre el [editor online](https://ravenbreeder.github.io/m3u-editor-pro-elite/).
2. Importa tu archivo o pega su contenido M3U y cárgalo.
3. Edita, organiza, fusiona o limpia los canales.
4. Exporta la lista y ábrela en tu reproductor compatible favorito.

Para editar sin Internet, guarda el [archivo index.html independiente](https://raw.githubusercontent.com/RavenBreeder/m3u-editor-pro-elite/main/index.html) y ábrelo en un navegador moderno. Las funciones de red requieren conexión y el almacenamiento de archivos locales depende del navegador.

### 🤝 Colabora con el proyecto

Puedes enviar sugerencias, informar de errores o contribuir mediante [GitHub Issues](https://github.com/RavenBreeder/m3u-editor-pro-elite/issues). Si te resulta útil, considera darle una estrella al repositorio. Utiliza listas ficticias o anonimizadas al reportar errores.

Esta herramienta es un editor de listas, no un servicio IPTV. No proporciona canales ni suscripciones. Úsala con contenido al que tengas autorización para acceder.

## ⚖️ License / Licencia

Released under the [MIT License](LICENSE). / Publicado bajo la [Licencia MIT](LICENSE).

**Developed by / Desarrollado por RavenBreeder.**
