# Nova Farma - Sistema de Inventario

Proyecto de gestión de inventario para farmacia, cumpliendo con la rúbrica ATF1.

## Estructura del Proyecto

```
/
├── index.html              → Dashboard (entrada principal)
├── README.md
├── README.txt              → Checklist de rúbrica
├── html/
│   ├── alertas.html        → Alertas de inventario
│   ├── inventario.html     → Cards de productos
│   └── registro.html       → Formularios de registro
└── assets/
    └── css/
        └── temas.css       → Estilos personalizados
```

Abre siempre **`index.html`** en la raíz. Las demás páginas están en **`html/`** y el menú lateral enlaza con rutas correctas.

## Características

- **Dashboard** en la raíz; **Alertas, Inventario y Registro** en `html/`
- **Navbar superior** + **sidebar izquierdo** (misma estética en todas las páginas)
- **Botón hamburguesa** solo en móvil/tablet (`d-lg-none`) para colapsar el sidebar
- **4 páginas** en total (1 + 3 en carpeta `html/`)
- Modales con `data-bs-toggle` y JS bundle de Bootstrap (CDN)

## Tecnologías

- HTML5, Bootstrap 5.3.3 (CDN), Bootstrap Icons (CDN), CSS en `assets/css/temas.css`

## Nota sobre JavaScript

No hay archivos `.js` propios. Solo `bootstrap.bundle.min.js` desde CDN (collapse del sidebar y modales).
