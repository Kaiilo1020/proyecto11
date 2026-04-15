================================================================
NOVA FARMA - SISTEMA DE INVENTARIO
Rubrica ATF1 - Entrega Final (Landing Page)
================================================================

1. ESTRUCTURA DE CARPETAS (ORGANIZADA)
================================================================

/ (raiz)
├── index.html              → Landing Page (Unico archivo HTML)
├── README.md               → Documentacion
├── README.txt              → Este archivo (checklist)
├── capturas/               → (Vacio por ahora, agregar mobile.png y desktop.png)
└── assets/
    ├── img/                → (Vacio por ahora, agregar logo y productos)
    └── css/
        └── temas.css       → Estilos personalizados minimos

NOTA: No hay archivos JavaScript propios. Solo se usa el JS bundle
de Bootstrap desde CDN para navbar collapse y modales.


2. CHECKLIST DE REQUISITOS RUBRICA ATF1
================================================================

[OK] Sitio estatico (1 landing completa - Opcion A)

[OK] Bootstrap CDN correctamente integrado (CSS + JS bundle)

[OK] Componentes obligatorios:
    - Navbar responsive con collapse (toggler) estandar en la parte superior ✓
    - Layout con grid (container + row + col-*) en multiples secciones ✓
    - Cards (minimo 4): 4 KPIs + 2 cards de formularios ✓
    - Tabla estilizada (table-striped, table-hover) en seccion Alertas e Inventario ✓
    - Imagenes responsive (img-fluid): preparadas en HTML (falta agregar archivos fisicos) ✓
    - Formulario con 4+ campos en seccion Registro (2 formularios) ✓
    - Modal de confirmacion (usando data-bs-toggle) ✓
    - Utilities Bootstrap: p-*, m-*, text-*, bg-*, rounded, shadow ✓

[OK] Responsive:
    - Navbar colapsa en movil (data-bs-toggle="collapse")
    - Grid adaptativo (se apilan las columnas en movil)


3. SECCIONES DE LA LANDING PAGE (index.html)
================================================================

#inicio      → Hero y 4 Cards de KPIs
#alertas     → Tabla estilizada de alertas de inventario
#inventario  → Tabla estilizada de inventario general
#registro    → 2 Formularios (Ingreso de mercaderia e Incidencias) con Modal


4. CDN USADO
================================================================

CSS: https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css
JS:  https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js
Icons: https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css


5. COMO ABRIR
================================================================

1. Descomprimir el ZIP
2. Abrir index.html en cualquier navegador
3. Navegar haciendo scroll o usando los enlaces del Navbar superior

================================================================
