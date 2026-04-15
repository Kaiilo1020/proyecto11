================================================================
NOVA FARMA - SISTEMA DE INVENTARIO
Rubrica ATF1 - Entrega Final
================================================================

1. ESTRUCTURA DE CARPETAS (ORGANIZADA)
================================================================

/ (raiz)
├── index.html              → Dashboard (KPIs + tabla) - ABRIR ESTE PRIMERO
├── README.md
├── README.txt              → Este archivo (checklist)
├── html/
│   ├── alertas.html        → Sistema de alertas
│   ├── inventario.html     → Cards de productos
│   └── registro.html       → Formularios de registro
└── assets/
    └── css/
        └── temas.css       → Estilos personalizados

NOTA: Solo hay UN index.html (en la raiz). No hay index duplicado en html/.

NOTA: No hay archivos JavaScript propios. Solo el JS bundle de Bootstrap (CDN)
para el collapse del sidebar y los modales.


2. CHECKLIST DE REQUISITOS RUBRICA ATF1
================================================================

[OK] Bootstrap CDN correctamente integrado (CSS + JS bundle)

[OK] Componentes obligatorios:
    - Navegacion responsive (sidebar con collapse en movil)
    - Layout con grid (container + row + col-*)
    - Cards (4 KPIs + inventario)
    - Tabla estilizada (table-striped, table-hover)
    - Formularios en html/registro.html
    - Modal de confirmacion (data-bs-toggle)
    - Utilities Bootstrap: p-*, m-*, text-*, bg-*, rounded, shadow

[OK] Responsive:
    - Movil: boton hamburguesa visible (d-lg-none), sidebar colapsable
    - Escritorio: sidebar siempre visible, sin hamburguesa


3. COMO ABRIR
================================================================

1. Descomprimir el ZIP
2. Abrir index.html (en la carpeta raiz del proyecto)
3. Navegar con el menu lateral a las paginas en html/


4. CDN USADO
================================================================

CSS: https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
JS:  https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js
Icons: https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css

================================================================
