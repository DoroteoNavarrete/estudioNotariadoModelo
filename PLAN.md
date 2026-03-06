# Estudio Notarial Modelo — Web Demo

## 🧠 Contexto del Agente (leer al inicio de cada sesión)

Eres un desarrollador frontend experto. Estás construyendo una **SPA demo** para vender a un cliente:
**Estudio Notarial Modelo**, Montevideo, Uruguay.

### Criterios globales del proyecto
- Stack: **HTML5 + CSS3 + JS Vanilla** — sin frameworks
- Diseño: **minimalista**, limpio, mucho espacio en blanco, profesional
- **Mobile-first**, totalmente responsive
- Todo el contenido generado (no confirmado por el cliente) lleva `<!-- TODO: ajustar con cliente -->` en el HTML
- No agregar dependencias externas salvo Google Fonts y Lucide Icons (CDN)

---

### Stack de archivos
```
index.html
css/
  styles.css
js/
  main.js
img/
  logo.png
  1767485260225.jpg         ← imagen principal (Hero)
  carrousel/
    Screenshot_1.png
    Screenshot_2.png
    Screenshot_3.png
```

---

### Paleta de colores

| Variable CSS       | Valor     | Uso                              |
|--------------------|-----------|----------------------------------|
| `--primary`        | `#254388` | Azul principal, headers, CTAs    |
| `--primary-hover`  | `#1c3370` | Hover sobre elementos primarios  |
| `--accent`         | `#3a5fbf` | Azul medio para detalles         |
| `--dark`           | `#1a1a2e` | Textos principales               |
| `--gray`           | `#6b7280` | Textos secundarios               |
| `--light-gray`     | `#f3f4f6` | Fondos de secciones alternas     |
| `--white`          | `#ffffff` | Fondos y textos sobre color      |

**Tipografía**: `Inter` via Google Fonts (400, 500, 600, 700)

---

### Datos del cliente

| Campo         | Valor                                                                 |
|---------------|-----------------------------------------------------------------------|
| Nombre        | Estudio Notarial Modelo                                               |
| Slogan        | "Te ayudamos a resolver tus trámites Notariales y Contables de forma clara, segura y eficiente." |
| Dirección     | Ángel María Cusano 3456, 11400 Montevideo, Departamento de Montevideo |
| WhatsApp      | +598 91 692 480 → `https://wa.me/59891692480`                         |
| Email         | contacto@estudionotarialmodelo.com.uy *(placeholder — confirmar)*     |
| LinkedIn      | https://www.linkedin.com/company/estudio-notarial-modelo/             |
| Google Maps   | https://maps.app.goo.gl/ouwwBixa1iWgh8de8                             |
| Horario       | Lunes a Sábado: 8:00–20:00 hs — Domingos: Cerrado                    |
| Rating Google | ⭐ 5.0                                                                |

---

### Servicios (generados — confirmar con cliente)

**Notariales**
- Compraventa de inmuebles
- Poderes notariales
- Sucesiones y herencias
- Certificaciones y autenticaciones
- Habilitaciones comerciales
- Constitución de sociedades

**Contables**
- Asesoramiento contable a empresas y personas
- Liquidación de impuestos (DGI / BPS)
- Gestión de nóminas
- Balances y estados financieros

---

### Reseñas (reales — Google)

1. **Valentina** — "¡Excelente servicio! Patricia es una escribana increíble que nos resolvió todas nuestras dudas."
2. **Gastón Rocha** — "Me fueron muy profesionales y amables los dos. Ya sé que si preciso algo voy con ellos."
3. **Maria Noel M** — "Excelentes profesionales. La escribana Patricia demuestra un profundo conocimiento en su área, transmitiendo confianza y seguridad en cada paso."
4. **Carol Curbelo** — "Excelente servicio! Muy buena atención y mucha agilidad con los trámites. Siempre se los recomiendo a todos."
5. **don antonio** — "Excelente disponibilidad! Tanto la escribana como el contador. Buen asesoramiento."

---

### Estructura de secciones (orden en la página)

1. **Navbar** — Logo + links ancla (Inicio, Servicios, Nosotros, Reseñas, Contacto) + botón CTA WhatsApp + hamburger mobile
2. **Hero** — Imagen `1767485260225.jpg` como fondo, headline, slogan, botón CTA
3. **Servicios** — Grilla de cards con íconos SVG (notariales + contables)
4. **Carrusel** — Sección con los 3 screenshots + controles prev/next + autoplay
5. **Nosotros** — Descripción del estudio, misión, valores
6. **Reseñas** — Cards con las reseñas de Google + badge ⭐ 5.0
7. **Contacto** — Dirección, horario, botón WhatsApp, iframe Google Maps, email, LinkedIn

---

## ✅ TODO LIST

### FASE 1 — Base
- [x] **TASK 1** — Crear `index.html`: estructura semántica completa, meta tags SEO básicos, importar Google Fonts (Inter), importar Lucide Icons CDN, links a `css/styles.css` y `js/main.js`, todas las secciones con sus `id` y contenido final

- [x] **TASK 2** — Crear `css/styles.css`: variables CSS, reset, tipografía, layout base, estilos de todas las secciones, navbar sticky, carrusel, cards servicios, cards reseñas, sección contacto, footer

### FASE 2 — Interactividad
- [x] **TASK 3** — Crear `js/main.js`: smooth scroll, navbar sticky con efecto al hacer scroll, mobile menu toggle (hamburger), carrusel autoplay + controles prev/next, animaciones fade-in on scroll (Intersection Observer)

### FASE 3 — Polish final
- [x] **TASK 4** — Revisión integral: responsive mobile/tablet/desktop, ajustes visuales finos, verificar todos los links y el botón de WhatsApp

---

*Stack: HTML + CSS + JS Vanilla | Última revisión del plan: Marzo 2026*
