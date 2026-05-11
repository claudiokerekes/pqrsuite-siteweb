# PQR Suite — Contexto del proyecto

## Producto

**PQR Suite** es un software SaaS de gestión de propiedad horizontal para Colombia. Centraliza la atención de peticiones, quejas y reclamos (PQR) de conjuntos residenciales, edificios y copropiedades, con inteligencia artificial integrada.

- **URL producción:** https://pqrsuite.com
- **App:** https://app.pqrsuite.com
- **WhatsApp ventas:** +57 314 567 8786
- **Google Analytics:** G-RET8SDQNM5

---

## Estructura de archivos

```
sitio_web_pqr/
├── index.html              # Página principal (landing page)
├── funcionalidades.html    # Página de funcionalidades
├── precios.html            # Página de planes y precios
├── demo.html               # Solicitar demo → redirige a WhatsApp
├── contacto.html           # Contacto → redirige a WhatsApp
├── styles.css              # CSS compartido por todas las páginas
├── favicon.svg             # Ícono del sitio
├── apple-touch-icon.png    # Ícono iOS 180×180px (degradado #4F46E5 → #06B6D4)
├── sitemap.xml             # Sitemap enviado a Google Search Console
├── robots.txt              # Allow: *, Sitemap: https://pqrsuite.com/sitemap.xml
└── CNAME                   # pqrsuite.com (GitHub Pages)
```

---

## Páginas y su propósito

| Página | URL | Propósito |
|---|---|---|
| Landing principal | `/` | Hero, features, IA, precios, testimonios, FAQ, CTA |
| Funcionalidades | `/funcionalidades.html` | Detalle de las 6 funciones + 2 cards destacadas |
| Precios | `/precios.html` | Tabla comparativa de planes |
| Demo | `/demo.html` | Botón WhatsApp + 4 beneficios de la demo |
| Contacto | `/contacto.html` | Botón WhatsApp + horario + info de soporte |

---

## Planes / Precios

| Plan | Precio | Unidades | Usuarios |
|---|---|---|---|
| Starter | $150.000 COP/mes | Hasta 100 | Hasta 5 |
| Esencial ⭐ | $250.000 COP/mes | Hasta 300 | Hasta 15 |
| Pro AI | $450.000 COP/mes | Hasta 400 | Hasta 25 |

- Todos incluyen 30 días de prueba gratuita
- Sin tarjeta de crédito
- Para más de 400 unidades: plan personalizado vía WhatsApp

---

## SEO

### Keywords objetivo
1. `gestión de propiedad horizontal`
2. `software de propiedad horizontal`
3. `administración de conjuntos`

### Meta tags (index.html)
- **Title:** `PQR Suite — Software para Gestión de Propiedad Horizontal` (57 chars)
- **Description:** `Software de propiedad horizontal para administración de conjuntos. Gestiona PQR con IA, primera respuesta en menos de 2 horas. Prueba gratis 30 días.` (149 chars)
- **Lang:** `es-CO` (todas las páginas)
- **Canonical:** `https://pqrsuite.com/`
- **hreflang:** `es-CO`
- **geo.region:** `CO`

### Schemas JSON-LD (index.html)
- `SoftwareApplication` — con featureList, offers, aggregateRating
- `Organization` — nombre, URL, logo, contactPoint
- `FAQPage` — 5 preguntas/respuestas sobre propiedad horizontal

### Sección FAQ visible (index.html)
5 preguntas con accordion interactivo que cubren los 3 keywords objetivo. También tienen microdata `itemscope`.

### Sitemap
Enviado a Google Search Console. Contiene las 5 URLs:
- `https://pqrsuite.com/`
- `https://pqrsuite.com/funcionalidades.html`
- `https://pqrsuite.com/precios.html`
- `https://pqrsuite.com/demo.html`
- `https://pqrsuite.com/contacto.html`

### Estado backlinks (abril 2026)
- 1 backlink, 1 dominio de referencia → sitio nuevo, requiere estrategia off-page
- Directorios recomendados para conseguir backlinks: Clutch, G2, Capterra, GetApp, Páginas Amarillas Colombia

---

## Diseño / UI

- **Stack:** HTML + CSS vanilla + JS vanilla (sin frameworks)
- **CSS:** extraído a `styles.css` compartido entre todas las páginas
- **Fuente:** Plus Jakarta Sans (Google Fonts)
- **Paleta:**
  - Fondo: `#06060a` (void) / `#0a0a10` (base)
  - Acento: `#4F46E5` (indigo) / `#6366F1` (light)
  - Cyan: `#06B6D4`
  - Emerald: `#10B981`
  - Texto: `#F1F5F9` (primary) / `#94A3B8` (secondary)
- **Estilo:** dark glassmorphism con blobs animados de fondo
- **Responsive:** breakpoints en 1100px, 768px, 480px

---

## Métricas del producto (mostradas en el sitio)

- +10.000 casos gestionados
- <2h primera respuesta promedio
- 95% tasa de resolución
- +350 edificios activos
- Rating: 4.8/5 (350 reseñas)
