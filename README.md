# FormalizApp

Landing page del proyecto universitario **FormalizApp**, una plataforma web dirigida a pequeñas empresas mineras (MAPE) del Perú para centralizar la gestión de su formalización minera y cumplimiento normativo.

---

## Descripción

FormalizApp permite a las empresas MAPE:

- Gestionar documentos legales, tributarios y ambientales en un solo lugar.
- Controlar vencimientos y obligaciones normativas mediante alertas automáticas.
- Registrar y dar seguimiento a operaciones mineras para mantener trazabilidad.
- Visualizar indicadores de cumplimiento y nivel de formalización.
- Simular fiscalizaciones para identificar riesgos antes de una inspección real.
- Extraer automáticamente información de documentos mediante OCR.

---

## Estructura del proyecto

```
formalizapp/
├── index.html        # Página principal (landing page)
├── css/
│   └── style.css     # Estilos globales
└── README.md         # Este archivo
```

---

## Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de la página |
| CSS3 | Estilos, layout y responsive design |
| JavaScript (Vanilla) | Animación 3D del fondo (hero) |
| Three.js r128 | Renderizado WebGL del terreno wireframe |
| Google Fonts – Inter | Tipografía |

> Three.js se carga desde CDN: `cdnjs.cloudflare.com`

---

## Secciones de la landing page

| Sección | ID | Descripción |
|---|---|---|
| Hero | `#hero` | Encabezado principal con fondo 3D animado |
| Módulos | `#caracteristicas` | Los 6 módulos de la plataforma |
| Cómo funciona | `#como-funciona` | Proceso en 3 pasos |
| Contacto | `#contacto` | Formulario de contacto y datos |

---



## Validaciones del formulario

| Campo | Validación |
|---|---|
| Nombre | Mínimo 3 caracteres, solo letras |
| Empresa | Mínimo 2 caracteres |
| RUC | Exactamente 11 dígitos numéricos |
| Correo | Formato de email válido |
| Teléfono | Exactamente 9 dígitos numéricos |
| Cargo | Selección obligatoria |
| Motivo | Selección obligatoria |
| Mensaje | Mínimo 10 caracteres |
| Términos | Aceptación obligatoria |

---

## Responsive

| Breakpoint | Comportamiento |
|---|---|
| > 960px | Grid de 3 columnas, layout completo |
| 600px – 960px | Grid de 2 columnas |
| < 600px | Grid de 1 columna, nav oculta, stats del hero ocultos |

---

## Público objetivo

- Gerentes y titulares de empresas MAPE.
- Responsables administrativos y de cumplimiento normativo.
- Supervisores de operaciones mineras.

---

## Autores

Proyecto universitario — Universidad Peruana de Ciencias Aplicadas (UPC) · 2025

---


## Licencia

Uso académico. Proyecto desarrollado con fines educativos.

## Demo
🔗 [Ver en GitHub Pages](https://nicolezutaprada-netizen.github.io/landingpage-minera/)