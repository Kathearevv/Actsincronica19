# Ejemplo 02 — API offline

Proyecto Vite + React + React Router + `vite-plugin-pwa`.

## Qué muestra

- `NetworkFirst` para las respuestas de DummyJSON;
- `CacheFirst` para imágenes;
- aviso de conexión perdida;
- prompt de actualización del service worker;
- navegación SPA con fallback a `index.html`.

## Comandos

```bash
npm install
npm run dev
npm run build
npm run preview
```

Para comprobar el modo offline: abrir el catálogo, esperar la carga, activar
“Offline” en DevTools > Network y recargar.
