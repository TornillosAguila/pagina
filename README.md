# Grupo Águila — Landing page (v3 · upgrade premium)

Sitio de una sola página (landing) para **Grupo Águila / Tornillos Águila, S.A. de C.V.**, distribuidora de mayoreo en Durango: tornillería, herramienta, ferretería, material eléctrico, refacciones, línea agrícola, pinturas y maquinaria (bombas y generadores Evans).

Esta es una **vista previa (v2)** para validación del cliente. Sitio estático, sin backend, listo para **GitHub Pages**.



---

## Ajustes v3.1

- La mascota del Bot ya **no trae el globo de WhatsApp en la mano** (imagen editada, `assets/img/mascota-bot.webp` y `mascota-bot-sinwa.png`).
- La **Guía Águila ya no se desplaza** entre esquinas: se **desmaterializa y rematerializa** con una animación tipo sistema (glitch por franjas, aberración cromática cian/magenta y línea de escaneo).
- Sin sombra de piso bajo la guía (diseño más limpio).
- La guía **voltea hacia el centro** de la página según la esquina donde aparece y es **15% más pequeña** (100px / 73px móvil).
- La mascota de la tarjeta "Bot Águila 24/7" ahora es más pequeña (132px) y ya no invade el texto del bloque.
- Se eliminó el bloque **Meta 2030**.

## Novedades v3 (upgrade premium)

- **Guía Águila 🦅** — la mascota del Bot Águila vuela entre las 4 esquinas de la pantalla y da un consejo distinto cada 6 segundos con datos reales de la empresa (Plataforma Águila, Bot 24/7, contactos, ubicación, horario, misión, visión, Meta 2030, valores, líneas, marcas). Con controles de pausa/cierre, memoria de sesión, `aria-live` y soporte de `prefers-reduced-motion`. Asset: `assets/img/mascota-bot.webp` (25 KB, optimizado desde el PNG original).
- **Preloader** con logo animado y **barra de progreso de scroll** en degradado ámbar.
- **Scroll suave (Lenis)** + **parallax y reveals (GSAP/ScrollTrigger)** vía CDN, con *degradación elegante*: si el CDN no carga, la página funciona igual con IntersectionObserver nativo.
- **Sección nueva "Ecosistema digital"**: tarjetas destacadas de Plataforma Águila B2B y Bot Águila 24/7 (con la mascota), borde cónico animado.
- **Sección nueva "Cómo cotizar"** (4 pasos) y **FAQ** con acordeón + datos estructurados `FAQPage` para SEO.
- **Meta 2030** con contadores animados (150 colaboradores · $250M · 3 tiendas).
- **Badge "Abierto / Cerrado ahora"** calculado en vivo con la hora de Durango (`Intl.DateTimeFormat`, zona America/Monterrey).
- Tarjetas de producto con **tilt 3D** y glow que sigue el cursor; botones **magnéticos** con brillo de barrido; enlace activo en el menú según sección visible.
- Botón **volver arriba**, focos de teclado visibles, mejoras SEO (canonical, Twitter Card, og:locale).
- Se respetó al 100% la colorimetría, tipografías y esencia de la v2. Respaldo del index anterior en `docs/index-v2-respaldo.html`.

---

## Estructura

```
grupo-aguila-site/
├── index.html                 ← Landing (HTML + CSS + JS en un archivo)
├── .nojekyll                  ← Evita el procesamiento Jekyll en GitHub Pages
├── robots.txt
├── sitemap.xml
├── LICENSE.txt
├── assets/
│   ├── img/
│   │   ├── logo-aguila.webp   ← Logo (águila + "Grupo Águila" en ámbar)
│   │   └── hero-poster.jpg    ← Imagen de respaldo del video del encabezado
│   └── video/
│       ├── grupo-aguila-hero.mp4   ← Video de fondo del encabezado (1080p, loop 8s)
│       └── grupo-aguila-hero.webm  ← Misma animación, mejor compresión
└── docs/
    └── proyecto.md            ← Documento maestro (análisis, propuesta, cronograma)
```

## Características

- Encabezado con **video de fondo** (motion graphics industrial) detrás del logo, con `poster` de respaldo.
- 7 líneas de producto, marcas ancla (Truper, Evans, Fischer), misión/visión/valores y cotizador por WhatsApp (618 818 2655).
- Acceso a **Plataforma Águila** (enlace, se mantiene intacto).
- SEO: meta tags, Open Graph, `sitemap.xml`, `robots.txt` y datos estructurados Schema.org (`HardwareStore`).
- 100% responsive. Sin dependencias de build (solo fuentes de Google).

---

## Cómo publicar en GitHub Pages

### Opción A — desde la interfaz web de GitHub
1. Crea un repositorio nuevo (ej. `grupo-aguila-site`).
2. Sube **todo el contenido de esta carpeta** (incluyendo la carpeta `assets/` y el archivo `.nojekyll`).
3. Ve a **Settings → Pages**.
4. En **Source**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
5. En 1–2 minutos el sitio queda en: `https://TU-USUARIO.github.io/grupo-aguila-site/`

### Opción B — desde la terminal (git)
```bash
cd grupo-aguila-site
git init
git add .
git commit -m "Preview v2 - landing Grupo Águila"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/grupo-aguila-site.git
git push -u origin main
```
Luego activa Pages en **Settings → Pages** (rama `main`, carpeta root).

> Tras publicar, reemplaza `TU-USUARIO` en `robots.txt` y `sitemap.xml` por tu usuario/repositorio reales.

---

## Pendientes (para la versión final)

- [ ] Logos reales de **Truper**, **Evans** y **Fischer** (reemplazan los recuadros "LOGO ...").
- [ ] **Fotos** de instalaciones y productos.
- [ ] **Embed real de Google Maps** (Masurio 200) en la sección Ubicación.
- [ ] Confirmar **horario de atención**.
- [ ] (Opcional) Sustituir el video de motion graphics por **metraje real** (mismas dimensiones y duración del loop).
- [ ] (Opcional) Conectar el formulario a correo/CRM además de WhatsApp.

## Datos del negocio

- **Razón social:** Tornillos Águila, S.A. de C.V.
- **Teléfono / WhatsApp:** 618 818 2655
- **Correo:** ventas@tornillosaguila.com
- **Domicilio:** Masurio 200, Col. Luis Echeverría, C.P. 34250, Durango, Dgo.
- **Lema:** "La superación es nuestro trabajo diario."
