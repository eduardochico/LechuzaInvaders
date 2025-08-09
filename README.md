# 🦉 Lechuza vs Águilas

**Lechuza vs Águilas** es un juego arcade estilo *Space Invaders*, donde controlas a una **valiente lechuza** que debe defenderse de oleadas de **águilas invasoras**.  
El proyecto está optimizado como **PWA** (Progressive Web App), con controles táctiles para móvil y posibilidad de instalarse como aplicación.

![Captura del juego](assets/screenshot.png)

---

## 🚀 Características

- **Estilo clásico arcade** con desplazamiento horizontal y disparos.
- **Sprites en SVG** para la lechuza y las águilas.
- **Controles**:
  - **Teclado**:  
    - `←` / `→`: mover  
    - `ESPACIO`: disparar  
    - `P`: pausar  
    - `M`: silenciar  
  - **Móvil**: botones táctiles siempre visibles.
- **PWA lista para instalar**:
  - `manifest.webmanifest` con íconos 192x192 y 512x512.
  - `service worker` para uso offline.
- **Escalado automático y responsive**:
  - Usa `100dvh` para ocupar toda la pantalla.
  - Mantiene proporción **4:3** en cualquier dispositivo.
  - Canvas centrado y escalado al máximo.
- **Animaciones**:
  - Fondo estrellado dinámico.
  - Explosiones de partículas al destruir enemigos.
- **Sonido** generado por Web Audio API (sin archivos externos).

---

## 📂 Estructura de archivos

