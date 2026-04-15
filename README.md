# Nova Farma - Sistema de Inventario (Landing Page)

Proyecto de gestión de inventario para farmacia, cumpliendo con la rúbrica ATF1 (Opción A: 1 landing completa).

## Estructura del Proyecto

```
/
├── index.html              → Landing Page (Unico archivo HTML)
├── README.md
├── README.txt              → Checklist de rúbrica
├── capturas/               → Carpeta para screenshots (desktop/mobile)
└── assets/
    ├── img/                → Carpeta para imágenes (logo)
    └── css/
        └── temas.css       → Estilos personalizados mínimos
```

Abre siempre **`index.html`** en la raíz. Todo el contenido está estructurado verticalmente en secciones (`#inicio`, `#alertas`, `#inventario`, `#registro`).

## Características

- **1 sola página** (Landing Page) según rúbrica ATF1 Opción A.
- **Navbar superior estándar** de Bootstrap con collapse (botón hamburguesa).
- **4 Cards de KPIs** en la sección Inicio.
- **Tablas estilizadas** en las secciones Alertas e Inventario (`table-hover`).
- **2 Formularios** de registro (Mercadería e Incidencias) con más de 4 campos.
- **Modal** de confirmación al enviar formulario (usando `data-bs-toggle`).
- **Sin JavaScript propio** — solo Bootstrap JS bundle desde CDN.

## Tecnologías

- HTML5
- Bootstrap 5.3.3 (CDN)
- Bootstrap Icons (CDN)
- CSS en `assets/css/temas.css`

## Cumplimiento Rúbrica ATF1

| Requisito | Estado |
|-----------|--------|
| Sitio estático (1 landing) | ✅ |
| Bootstrap CDN (CSS + JS bundle) | ✅ |
| Navbar responsive con collapse | ✅ (Estándar superior) |
| Layout con grid system | ✅ |
| Cards (mínimo 4) | ✅ (6 cards totales) |
| Tabla estilizada | ✅ |
| Imágenes responsive (img-fluid) | ✅ (Preparadas en HTML) |
| Formulario 4+ campos | ✅ (2 formularios) |
| Modal de confirmación | ✅ |
| Utilities Bootstrap (>6) | ✅ |
| Responsive | ✅ |

## Nota sobre JavaScript

No hay archivos `.js` propios en el proyecto. Se usa exclusivamente:
- `bootstrap.bundle.min.js` desde CDN (para navbar collapse y modales)
- Los modales se activan con atributos `data-bs-toggle="modal"` (sin JS manual)
