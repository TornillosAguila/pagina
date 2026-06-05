# Proyecto: Rediseño y Nueva Landing Page — Tornillos Águila

> **Documento maestro del proyecto.** Contiene la auditoría del sitio actual, la propuesta técnica avanzada, el cronograma de desarrollo y el plan de trabajo.
> **Rol del autor:** Senior Developer · Tech Lead · Software Architect
> **Cliente:** Tornillos Águila, S.A. de C.V. (Ferretería / Grupo Águila)
> **Sitio actual:** https://tornillosaguila.com
> **Fecha del documento:** 2026-06-01
> **Versión:** 2.0 — incorpora el *Cuadro Ejecutivo Institucional*, el número oficial (618 818 2655) y el preview navegable de la landing. La Plataforma Águila se mantiene intacta; la plataforma proveedora queda fuera de alcance.
>
> **Entregables asociados a esta versión:**
> - `grupo-aguila-landing-preview.html` — preview navegable del proyecto (prototipo funcional con datos reales y placeholders para fotos).

---

## Índice

1. [Resumen ejecutivo](#1-resumen-ejecutivo)
2. [Datos de negocio extraídos](#2-datos-de-negocio-extraídos)
3. [Auditoría técnica del sitio actual](#3-auditoría-técnica-del-sitio-actual)
4. [Hallazgos críticos](#4-hallazgos-críticos)
5. [Análisis DAFO](#5-análisis-dafo)
6. [Propuesta de landing page avanzada](#6-propuesta-de-landing-page-avanzada)
7. [Arquitectura técnica propuesta](#7-arquitectura-técnica-propuesta)
8. [Cronograma de desarrollo](#8-cronograma-de-desarrollo)
9. [Plan de trabajo](#9-plan-de-trabajo)
10. [Riesgos y mitigaciones](#10-riesgos-y-mitigaciones)
11. [Estimación de esfuerzo y costos](#11-estimación-de-esfuerzo-y-costos)
12. [Anexos](#12-anexos)

---

## 1. Resumen ejecutivo

Tornillos Águila es una distribuidora de tornillería, herramienta y soluciones de fijación con sede en Durango, Dgo. (Masurio 200, Col. Luis Echeverría). Su sitio actual es un **template gratuito de 2019 sin personalizar** (Paper Kit de Creative Tim sobre Bootstrap 4), alojado en GitHub Pages, con contenido mínimo, SEO inexistente y contenido que ya no refleja su giro real de mayoreo multisectorial.

El objetivo de este proyecto es entregar una **landing page moderna, rápida y orientada a conversión** que:

- Proyecte la imagen de una distribuidora seria y confiable (B2B + B2C).
- Capte leads (cotizaciones por WhatsApp / formulario) de forma medible.
- Posicione la marca en búsquedas locales ("tornillos Durango", "ferretería Durango", "Fischer / Truper / Evans Durango").
- Sirva de puerta de entrada ordenada hacia los catálogos y conserve el acceso a la **Plataforma Águila** existente.

**Diagnóstico en una línea:** el sitio actual no es un activo de negocio, es un folleto desactualizado. La oportunidad de mejora es muy alta y de bajo costo relativo.

---

## 2. Datos de negocio extraídos

### 2.1 Identidad

| Campo | Valor |
|---|---|
| Razón social | Tornillos Águila, S.A. de C.V. |
| Marca comercial | Grupo Águila / Tornillos Águila / Ferretería Grupo Águila |
| Giro | **Distribuidora de mayoreo** en sector ferretero, eléctrico, refaccionario, tornillero, agrícola, pinturas y complementos |
| Domicilio | Masurio (Mazurio) No. 200, Col. Luis Echeverría, C.P. 34250, Durango, Dgo., México |
| Lema institucional | **"La superación es nuestro trabajo diario."** |

> 📄 **Fuente actualizada (jun-2026):** *Cuadro Ejecutivo Institucional* aportado por el cliente. Reemplaza la misión/visión que figuraban en el sitio antiguo y amplía el giro de "tornillería" a **mayoreo multisectorial**.

### 2.2 Contacto

| Canal | Dato |
|---|---|
| Teléfono / WhatsApp **oficial** | **618 818 2655** (`wa.me/526188182655`) ✅ confirmado por el cliente |
| Email ventas | ventas@tornillosaguila.com |
| Email gerencia | gerencia@tornillosaguila.com |
| Facebook | facebook.com/ferreteriagrupoaguila |

> El número oficial quedó confirmado: **618 818 2655**. Se descarta el segundo número que circulaba en el sitio anterior.

### 2.3 Propuesta de valor y líneas de producto

Grupo Águila es una **distribuidora de mayoreo** que cubre siete líneas de producto, posicionándose como proveedor único para obra, industria, taller, campo y comercio.

**Siete líneas de producto:**

1. **Ferretero** — material ferretero general.
2. **Eléctrico** — soluciones eléctricas e iluminación.
3. **Refaccionario** — refacciones y accesorios.
4. **Tornillero** — tornillería general, milimétrica, inoxidable, galvanizada en caliente, con PTFE azul, para estructura metálica, madera, prefabricados y válvulas.
5. **Agrícola** — productos y complementos para el campo.
6. **Pinturas** — pinturas, recubrimientos y acabados.
7. **Complementos** — accesorios que cierran cualquier proyecto.

**Tres marcas ancla (respaldo de marca):**

1. **Truper** — refacciones, accesorios y herramienta.
2. **Evans** — soluciones en **Agua y Energía** para hogar, negocio e industria.
3. **Fischer** — soluciones de **fijación** en acero, química y nylon.

### 2.4 Misión, visión, meta y valores (Cuadro Ejecutivo Institucional)

- **Misión:** consolidarnos como una empresa de mayoreo líder en el sector ferretero, eléctrico, refaccionario, tornillero, agrícola, pinturas y complementos; satisfaciendo las necesidades de nuestros clientes mediante productos de óptima calidad, respaldados por un servicio eficiente, confiable y profesional.
- **Visión:** ser una empresa confiable y líder a nivel regional en la comercialización de nuestros productos, ofreciendo un amplio surtido, disponibilidad inmediata, calidad y un enfoque permanente en la mejora continua.
- **Meta 2030:** ser un grupo empresarial sólido integrado por un corporativo y tres tiendas especializadas, con 150 colaboradores, ventas anuales por $250 millones de pesos y una utilidad del 20%.
- **Valores organizacionales:** trabajo en equipo · respeto y empatía · servicio y calidad · honestidad · responsabilidad y compromiso · mejora continua.

> Estos textos son los **oficiales** para usar en la web (secciones Nosotros / Misión-Visión / Valores).

---

## 3. Auditoría técnica del sitio actual

### 3.1 Stack detectado

| Capa | Tecnología | Estado |
|---|---|---|
| Plantilla base | **Paper Kit 2.2.0** (Creative Tim) | Gratuita, de 2019, sin personalizar |
| Framework CSS | **Bootstrap 4.3.1** | Obsoleto (Bootstrap 5.3 es el actual) |
| JS | **jQuery + Popper.js** | Patrón legado |
| Preprocesador | **SCSS** compilado con Gulp | OK como concepto |
| Build | **Gulp 3.9.1** + `gulp-sass 4.0.1` (node-sass) | Toolchain deprecada y difícil de instalar hoy |
| Hosting | **GitHub Pages** + dominio propio | Adecuado para estático, mal aprovechado |
| Arquitectura | Multipágina estática: `inicio.html`, `conocenos.html`, `catalogos.html`, `instalaciones.html` | Sin CMS, sin backend, sin base de datos |
| Peso de assets | ~26 MB (imágenes sin optimizar + demo del template) | Excesivo |

Composición de lenguajes del repo: CSS 46% · SCSS 44% · HTML 8% · JS 2% → confirma que es **casi puro template, con muy poca lógica propia**.

### 3.2 Inventario de páginas

- **inicio.html** — hero, tres tarjetas (Truper / Evans / Fischer), formulario de contacto que **redirige a WhatsApp por JS** (sin backend ni validación).
- **conocenos.html** — misión y visión, poco más.
- **catalogos.html** — prácticamente vacía (sólo navbar + footer); no hay catálogo consultable en el sitio.
- **instalaciones.html** — carrusel de fotos de las instalaciones.

### 3.3 Auditoría por dimensiones

| Dimensión | Calificación | Observaciones |
|---|---|---|
| **SEO** | 🔴 Muy bajo | `<title>` vacío, sin meta description, sin Open Graph, sin datos estructurados (LocalBusiness), sin sitemap ni robots optimizado. |
| **Rendimiento** | 🟠 Bajo | ~26 MB de assets, imágenes JPG/PNG sin comprimir ni `webp`/`avif`, CSS/JS de template completo sin tree-shaking. |
| **Accesibilidad (a11y)** | 🟠 Bajo | Sin estructura semántica revisada, contraste y `alt` no auditados, formulario sin labels asociados correctamente. |
| **Seguridad** | 🟠 Media | Sitio estático sin backend; el formulario expone número por JS. Sin headers de seguridad. |
| **UX / Conversión** | 🟠 Bajo | Sin CTA claro y jerarquizado, sin prueba social, sin información de horarios/ubicación destacada, catálogo inaccesible. |
| **Contenido** | 🔴 Muy bajo | Restos del template (mapa apunta a "Twitter Inc., San Francisco", enlaces a CreativeTim, imágenes demo de personas/banderas sin relación con el negocio). |
| **Mantenibilidad** | 🟠 Media-baja | Toolchain Gulp 3 difícil de reconstruir; mezcla de archivos demo y propios. |
| **Mobile** | 🟠 Media | Hereda responsive de Bootstrap pero con `maximum-scale=1.0, user-scalable=0` (anti-patrón de accesibilidad). |

---

## 4. Hallazgos críticos

> Nota de alcance: por indicación del cliente, **la Plataforma Águila se deja intacta** (se conserva tal cual el acceso/enlace existente) y **la plataforma proveedora queda fuera del alcance** de este proyecto. No se analiza ni se interviene.

1. **🔴 Restos del template sin configurar.** El mapa de Google apunta a *"Twitter, Inc., Market Street, San Francisco"*, los enlaces sociales van a `@CreativeTim` y a los demos de Creative Tim. Daña credibilidad de inmediato.

2. **🟠 SEO inexistente.** Una distribuidora local **debe** rankear en búsquedas locales; hoy es invisible para Google más allá del nombre exacto.

3. **🟠 Activos pesados e irrelevantes.** Decenas de imágenes demo (rostros, banderas de países) que no se usan, inflando el repo a 26 MB.

4. **🟠 Formulario sin backend.** El "contacto" sólo arma un texto y redirige a `wa.me`. No hay registro de leads, validación ni anti-spam si WhatsApp falla.

5. **🟠 Contenido desactualizado.** El sitio sólo refleja tornillería; no comunica el giro real de **mayoreo en 7 líneas** ni los textos institucionales nuevos.

---

## 5. Análisis DAFO

| Fortalezas | Debilidades |
|---|---|
| Marca establecida y con trayectoria en Durango | Sitio = template genérico sin identidad |
| Marcas ancla reconocidas (Truper, Evans, Fischer) | SEO nulo, sin tráfico orgánico |
| Catálogo amplio y especializado | Contenido web desactualizado (sólo tornillería) |
| Dominio propio ya configurado | Sin captura ni seguimiento de leads |

| Oportunidades | Amenazas |
|---|---|
| Posicionamiento local SEO de bajo costo | Competidores con e-commerce/marketplace |
| Cotización rápida vía WhatsApp Business | Pérdida de confianza por "sitio no seguro" |
| Catálogo digital y ficha Google Business | Plantilla obsoleta difícil de mantener |
| Segmentar B2B (constructoras, industria) vs B2C | Sin captura ni seguimiento de leads |

---

## 6. Propuesta de landing page avanzada

### 6.1 Objetivos y KPIs

| Objetivo | KPI | Meta inicial |
|---|---|---|
| Captar leads | Cotizaciones (WhatsApp + formulario) / mes | +50% vs. hoy |
| Posicionamiento local | Top-3 en "tornillos/ferretería Durango" | 3–6 meses |
| Rendimiento | Core Web Vitals (LCP/INP/CLS) | LCP < 2.0s, INP < 200ms, CLS < 0.1 |
| Confianza | Tasa de rebote | < 55% |
| Alcance | Tráfico orgánico mensual | Crecimiento sostenido |

### 6.2 Arquitectura de información (one-page + secciones)

Landing principal (scroll único) con anclas, más páginas de soporte ligeras:

1. **Header / Navbar fijo** — logo, anclas (Productos, Marcas, Nosotros, Ubicación, Contacto), CTA "Cotizar por WhatsApp" y acceso a la **Plataforma Águila** (enlace existente, intacto).
2. **Hero** — propuesta de valor clara ("Distribuidora de tornillería, herramienta y fijación en Durango"), CTA primario (Cotizar) y secundario (Ver catálogo).
3. **Líneas de producto** — tarjetas: Tornillería · Fijación (Fischer) · Agua y Energía (Evans) · Herramienta (Truper) · Refacciones.
4. **Marcas que manejamos** — grid de logos (prueba social/credibilidad).
5. **Catálogo destacado / buscador** — categorías navegables (las 7 líneas) + buscador y descarga de catálogos PDF.
6. **¿Por qué Águila?** — diferenciadores: surtido, disponibilidad, asesoría, trayectoria, servicio a industria/constructora.
7. **Cotizador / Contacto** — formulario con backend (lead capture + WhatsApp como canal preferente), datos de contacto y horarios.
8. **Ubicación** — mapa real embebido (Masurio 200) + indicaciones + horarios.
9. **Footer** — contacto, redes reales, aviso de privacidad, RFC/legal.

Páginas de soporte: `Conócenos` (misión/visión/instalaciones), `Catálogos`, `Aviso de Privacidad`.

### 6.3 Funcionalidades clave

- **Cotizador inteligente:** formulario con validación + envío a backend (correo/CRM) **y** prearmado de mensaje de WhatsApp Business como fallback. Anti-spam (honeypot + rate limit / captcha invisible).
- **Buscador de catálogo:** filtrado por categoría/medida/material sobre un índice estático (JSON) — sin necesidad de backend pesado.
- **Catálogos descargables:** PDFs versionados y optimizados.
- **Acceso a Plataforma Águila:** se conserva el enlace de acceso actual, intacto (fuera de alcance del rediseño).
- **Click-to-call / Click-to-WhatsApp** persistente en móvil.
- **i18n-ready** (es por defecto; estructura lista por si se requiere inglés industrial).

### 6.4 SEO técnico y local

- `<title>` y `meta description` por página; Open Graph + Twitter Cards.
- **Datos estructurados Schema.org `LocalBusiness` / `HardwareStore`** con dirección, geo, horarios y teléfono.
- Sitemap.xml + robots.txt; URLs limpias.
- Optimización de **Google Business Profile** (paralelo, fuera del código).
- Contenido orientado a intención local y por marca.

### 6.5 Rendimiento

- Imágenes en **AVIF/WebP** con `srcset` y `loading="lazy"`; presupuesto de página < 1 MB en el primer view.
- CSS/JS con tree-shaking; crítico inline; resto diferido.
- Fuentes con `font-display: swap`, self-host si es viable.
- CDN (incluido por el hosting recomendado).

### 6.6 Accesibilidad

- HTML semántico, contraste AA, `alt` reales, navegación por teclado.
- Quitar `user-scalable=0` (permitir zoom).
- Formularios con labels y mensajes de error accesibles.

### 6.7 Analítica y medición

- Google Analytics 4 + eventos de conversión (clic WhatsApp, envío de formulario, descarga de catálogo, clic a Plataforma Águila).
- Google Search Console.
- Consentimiento de cookies (aviso de privacidad) conforme a buenas prácticas.

---

## 7. Arquitectura técnica propuesta

### 7.1 Decisión de arquitectura (visión de Architect)

El sitio es **mayormente contenido + captación de leads**, no una app compleja. Se recomienda **arquitectura estática moderna (Jamstack)**: máxima velocidad, mínimo costo, máxima seguridad (sin superficie de servidor) y excelente SEO.

**Opción recomendada (A):**

| Capa | Tecnología | Justificación |
|---|---|---|
| Framework | **Astro** (con islas React/Vue opcionales) | Genera HTML estático ultraligero; JS sólo donde se necesita. Ideal para landing + SEO. |
| Estilos | **Tailwind CSS** | Productividad, consistencia, bundle pequeño. |
| Contenido | **Markdown/JSON + Content Collections** (o CMS headless ligero como **Decap/Sanity** si el cliente quiere editar) | Permite que el cliente actualice productos/catálogos sin tocar código. |
| Formularios | **Serverless function** (Cloudflare Workers / Netlify Functions) → email + WhatsApp | Captura de leads sin servidor permanente. |
| Hosting | **Cloudflare Pages / Netlify / Vercel** | CDN global, HTTPS automático, CI/CD desde Git, gratis o muy bajo costo. |
| Repositorio/CI | **GitHub + GitHub Actions** | Despliegue automático en cada push; previews por PR. |

**Opción alternativa (B) — mínima fricción:** mantener HTML/CSS modernos (Bootstrap 5 o Tailwind) **sin** framework, sólo migrando build a **Vite**. Más barata, menos escalable.

> Recomendación del Tech Lead: **Opción A (Astro + Tailwind + Cloudflare Pages)** por equilibrio costo/rendimiento/SEO/mantenibilidad.

### 7.2 Diagrama lógico

```
[Usuario]
   │  HTTPS
   ▼
[Cloudflare CDN/Pages] ── HTML/CSS/JS estático (Astro build)
   │                         ├─ /catalogo (índice JSON + buscador)
   │                         ├─ /pdf catálogos (optimizados)
   │                         └─ assets WebP/AVIF
   │
   ├─ POST /api/lead ─► [Serverless Function] ─► Email (ventas@) + log/CRM
   │                                          └─► (fallback) WhatsApp Business
   │
   └─ Enlace "Plataforma Águila" ─► se conserva el acceso actual (fuera de alcance)
```

### 7.3 Seguridad

- HTTPS en todo el sitio nuevo (automático en el hosting recomendado).
- Headers de seguridad (CSP, HSTS, X-Content-Type-Options).
- Validación y rate-limit en la función de leads; honeypot anti-bots.
- Sin secretos en el cliente; variables en el panel del hosting.

### 7.4 Calidad y DevOps

- **Linters/formatters** (ESLint, Prettier, Stylelint).
- **Lighthouse CI** en cada PR (presupuestos de rendimiento/SEO/a11y).
- **Previews automáticos** por rama; despliegue a producción sólo desde `main`.
- Convención de commits y CHANGELOG.

---

## 8. Cronograma de desarrollo

Estimación base: **~6 semanas** (≈ 1 desarrollador full-stack + apoyo de diseño y contenidos). Ajustable según disponibilidad de activos del cliente (logos en alta, fotos, catálogos PDF, textos definitivos).

### 8.1 Fases y entregables

| Fase | Duración | Entregables |
|---|---|---|
| **F0 — Descubrimiento y kickoff** | 3 días | Validación de datos de contacto, accesos, inventario de activos, definición de alcance y KPIs. |
| **F1 — UX/UI y contenido** | 1 semana | Wireframes, sistema de diseño (colores/tipografía/logo), copy SEO, mapa del sitio. |
| **F2 — Arquitectura y setup** | 3 días | Repo, CI/CD, hosting, base Astro+Tailwind, pipeline de imágenes. |
| **F3 — Maquetado de secciones** | 1.5 semanas | Hero, productos, marcas, nosotros, ubicación, footer; responsive y a11y. |
| **F4 — Funcionalidad** | 1 semana | Cotizador (form + serverless + WhatsApp), buscador de catálogo, descargas PDF, analítica. |
| **F5 — SEO, rendimiento y QA** | 4 días | Schema, sitemap, OG, Lighthouse > 90, pruebas cross-browser/dispositivo. |
| **F6 — Lanzamiento y handoff** | 2 días | Deploy a dominio, Search Console/GA4, capacitación, documentación. |
| **F7 — Soporte post-lanzamiento** | 2 semanas (opcional) | Ajustes, medición inicial, optimización. |

### 8.2 Gantt textual (semanas)

```
Semana →        1      2      3      4      5      6
F0 Kickoff     ██
F1 UX/UI       ░█████
F2 Setup           ██
F3 Maquetado        ░████████
F4 Funcional               ░██████
F5 SEO/QA                        ░████
F6 Lanzamiento                        ░██
F7 Soporte                              ░░░░░░ (post)
```

### 8.3 Hitos (milestones)

- **M1 (fin S1):** diseño aprobado + contenido base.
- **M2 (fin S3):** sitio navegable en staging.
- **M3 (fin S5):** funcionalidad completa + QA aprobado.
- **M4 (fin S6):** producción en vivo + analítica activa.

---

## 9. Plan de trabajo

### 9.1 Equipo y roles (RACI)

| Actividad | Dev/Tech Lead | Diseño | Contenido/SEO | Cliente |
|---|---|---|---|---|
| Definición de alcance | R | C | C | A |
| Diseño UI | C | R | C | A |
| Desarrollo | R | C | I | I |
| Contenido y catálogos | C | I | R | A/C |
| SEO técnico | R | I | C | I |
| QA | R | C | C | C |
| Lanzamiento | R/A | I | I | A |

R=Responsable · A=Aprobador · C=Consultado · I=Informado

### 9.2 Insumos requeridos del cliente (bloqueantes)

- [ ] Logo en vectorial (SVG/AI) y guía de color si existe.
- [ ] Fotos reales de instalaciones y productos (alta resolución).
- [ ] Catálogos en PDF actualizados por marca/categoría.
- [ ] Datos de contacto **confirmados** (teléfono y WhatsApp oficiales).
- [ ] Horarios de atención y ubicación exacta (para Google Business/mapa).
- [ ] Accesos: dominio (DNS) y repositorio.
- [ ] Aviso de privacidad / datos legales (RFC, razón social).

### 9.3 Definición de "Hecho" (Definition of Done)

- Lighthouse ≥ 90 en Performance, SEO, Best Practices y Accessibility.
- Responsive verificado en móvil, tablet y escritorio.
- Formulario probado (recepción de lead + WhatsApp).
- Schema, sitemap, robots, OG y favicon correctos.
- Sin enlaces/contenido residual de plantillas.
- HTTPS válido y headers de seguridad activos.
- Documentación de mantenimiento entregada.

### 9.4 Estrategia de migración y "go-live"

1. Construir en staging (subdominio o URL de preview).
2. Validación con cliente + ajustes.
3. Apuntar DNS al nuevo hosting con TTL bajo (rollback rápido).
4. Verificar SSL, redirecciones 301 desde `inicio.html` → `/`.
5. Activar GA4 + Search Console + envío de sitemap.
6. Monitoreo 72h post-lanzamiento.

---

## 10. Riesgos y mitigaciones

| Riesgo | Prob. | Impacto | Mitigación |
|---|---|---|---|
| Cliente tarda en entregar activos (fotos/catálogos) | Alta | Alto | Lista de insumos al kickoff; placeholders temporales; cronograma con holgura. |
| Expectativa de e-commerce completo | Media | Alto | Definir alcance: landing + leads ahora; e-commerce como fase 2. |
| Pérdida temporal de SEO al migrar | Baja | Medio | 301 desde URLs antiguas; mantener dominio; sitemap nuevo. |
| Toolchain antigua dificulta reuso de assets | Media | Bajo | Reconstruir desde cero con stack moderno; reutilizar sólo imágenes válidas. |

---

## 11. Estimación de esfuerzo y costos

> Rangos orientativos para una landing profesional con captación de leads (no incluye e-commerce ni intervención sobre la Plataforma Águila). Cifras a ajustar según mercado y acuerdos.

| Paquete | Alcance | Esfuerzo aprox. |
|---|---|---|
| **Esencial** | Landing one-page + SEO + cotizador WhatsApp/form + hosting | ~80–100 h |
| **Recomendado** | Esencial + buscador de catálogo + CMS ligero editable + analítica avanzada | ~120–160 h |
| **Avanzado** | Recomendado + multilenguaje + integración CRM + automatizaciones de leads | ~180–240 h |

**Costos recurrentes estimados (anuales):** dominio (ya existente), hosting CDN (gratis–bajo en Cloudflare/Netlify), correo profesional, opcional CMS headless. La mayoría del stack propuesto tiene tier gratuito suficiente para este tráfico.

---

## 12. Anexos

### 12.1 Stack actual vs. propuesto (resumen)

| | Actual | Propuesto |
|---|---|---|
| Framework | Bootstrap 4 + jQuery | Astro + Tailwind (islas opcionales) |
| Build | Gulp 3 (node-sass) | Vite (incluido en Astro) |
| Hosting | GitHub Pages | Cloudflare Pages / Netlify |
| Contenido | HTML estático manual | Content Collections / CMS headless |
| Formularios | Redirección JS a WhatsApp | Serverless + email + WhatsApp |
| SEO | Inexistente | Schema, OG, sitemap, CWV optimizados |
| Plataforma Águila | Acceso existente | Se conserva intacto (fuera de alcance) |

### 12.2 Checklist pre-lanzamiento

- [ ] Títulos y meta descriptions únicos por página
- [ ] Open Graph + favicon + apple-touch-icon
- [ ] Schema LocalBusiness validado
- [ ] sitemap.xml + robots.txt
- [ ] GA4 + Search Console + eventos de conversión
- [ ] Formulario y WhatsApp probados extremo a extremo
- [ ] Lighthouse ≥ 90 (4 categorías)
- [ ] Sin contenido/enlaces residuales del template
- [ ] HTTPS + headers de seguridad
- [ ] Aviso de privacidad publicado
- [ ] Mapa apuntando a Masurio 200 (no a "Twitter SF")

### 12.3 Fuentes del análisis

- Sitio actual (`tornillosaguila.com`) y su código fuente público (repo `JorgeEGallardo/TornillosAguila` en GitHub): stack, páginas y assets.
- Directorios (Cosmos, Cylex, Coparmex) y redes (Facebook "Ferretería Grupo Águila"): contacto, productos y marcas.
- **Cuadro Ejecutivo Institucional** (cliente, jun-2026): misión, visión, meta 2030, valores y lema.

### 12.4 Pendientes de validación con el cliente

1. Activos de marca y fotos de la empresa (el cliente los enviará para integrarlos).
2. Confirmar horario de atención exacto para la sección Ubicación.
3. Alcance futuro: ¿landing de leads o evolución a e-commerce/catálogo transaccional?
4. ¿Quién editará el contenido? (define si se incluye CMS).

---

*Documento vivo. Próxima iteración: incorporar wireframes y la guía de marca una vez recibidos los activos del cliente.*
