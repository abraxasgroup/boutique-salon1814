# Boutique Salon 1814 — Landing Page

Landing page profesional para salones de belleza, nail studios y spas.
Desarrollada por **[Abraxas Group](https://abraxas-group.lat)**.

---

## 🚀 Demo en vivo

[abraxasgroup.github.io/boutique-salon1814](https://abraxasgroup.github.io/boutique-salon1814)

---

## ✏️ Cómo personalizar para un nuevo cliente

Abrí `index.html` y buscá el objeto `SALON` al inicio del `<script>` (línea ~60).
Editá solo ese bloque — el resto se actualiza automáticamente.

```js
const SALON = {
  nombre:    "Nombre del Salón",
  duena:     "Nombre de la dueña",
  ciudad:    "Ciudad, Provincia",
  whatsapp:  "549XXXXXXXXXX",     // sin + ni espacios
  instagram: "handle_sin_arroba",
  waTexto:   "Hola, quiero reservar un turno 💅",

  servicios: [ /* editá títulos e ítems */ ],
  precios:   [ /* editá nombres, precios e ítems */ ],
  testimonios: [ /* editá nombres y textos */ ],
  galeria:   [ /* reemplazá URLs por fotos del cliente */ ],
};
```

**Foto de fondo del hero:** reemplazá `img/local-hero.jpg` con la foto del local.

---

## 📦 Estructura del proyecto

```
boutique-salon1814/
├── index.html        ← todo el sitio (HTML + CSS + JS en un solo archivo)
└── img/
    └── local-hero.jpg  ← foto de fondo del hero
```

---

## 🛠 Stack

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica |
| Tailwind CSS (CDN) | Estilos utility-first |
| Google Fonts | Cormorant Garamond + DM Sans |
| Vanilla JS | Lógica de config, render dinámico, scroll reveal |
| Unsplash | Imágenes de galería (placeholder) |
| ui-avatars.com | Avatares de testimonios |

---

## 📋 Secciones incluidas

- **Hero** — foto de fondo, headline, mini-menú de servicios, CTA WhatsApp
- **Galería** — grid masonry de 6 fotos (reemplazables)
- **Servicios** — 3 categorías con ítems
- **Precios** — 3 packs con destacado central
- **Testimonios** — 3 reviews con avatar generado
- **Cursos** — sección "próximamente" con lista de espera
- **Sobre la dueña** — bio + link a Instagram
- **Abraxas Pitch** — sección B2B para captar nuevos clientes (editá el número de WA)
- **Footer** — links, redes, crédito Abraxas
- **Botón flotante** WhatsApp con animación pulse

---

## 🌐 Deploy en GitHub Pages

1. Ir a `Settings → Pages`
2. Source: `main` branch → `/root`
3. Guardar → listo en ~60 segundos

---

## 📞 ¿Querés una web así para tu salón?

**Abraxas Group** — diseño y lanzamiento en 72hs.

→ [abraxas-group.lat](https://abraxas-group.lat)
