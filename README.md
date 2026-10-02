<p align="center"><img src="icons/icon-192.png" width="96" alt="Logo Tracker de Alquileres"></p>

# Tracker de Alquileres

App web instalable (PWA) para llevar los **ingresos, gastos y fijos** de las viviendas en alquiler
(Madrid y Donostia): resumen por vivienda y año, registro de movimientos, gastos/ingresos fijos que
se apuntan solos cada mes y copia de seguridad.

**Abrir la app:** https://USUARIO.github.io/alquileres/

## Instalarla

- **Android / Chrome / Edge (PC):** abre el enlace → menú ⋮ → *Instalar app* (o desde *Datos → Instalar la app*).
- **iPhone / iPad (Safari):** abre el enlace → *Compartir* → *Añadir a pantalla de inicio*.

Funciona sin conexión una vez abierta.

## Dónde se guardan los datos

1. **Siempre en el propio dispositivo** (almacenamiento del navegador).
2. **Opcional: sincronizados entre todos tus dispositivos** a través de un *gist secreto* de tu cuenta de GitHub.
   En la app: **Datos → Sincronizar entre dispositivos** → crea un token con permiso solo de `gist`
   y pégalo en cada dispositivo. La app fusiona los cambios (gana la edición más reciente y respeta los borrados).

Los datos **nunca** se guardan en este repositorio. Además, en *Datos* puedes descargar o restaurar una copia `.json`.

## Estructura

| Archivo | Para qué |
|---|---|
| `index.html` | La app completa (interfaz de escritorio y de móvil) |
| `manifest.webmanifest` | Nombre, colores e iconos para instalarla |
| `sw.js` | Service worker: uso sin conexión |
| `icons/` | Logo e iconos |
