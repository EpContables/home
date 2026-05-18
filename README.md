# Ep Contables - Sitio Web Oficial

Repositorio oficial del sitio web para **Ep Contables**, especialistas en gestión tributaria y contable digital en Chile.

🌍 **Sitio web:** [https://epcontables.github.io/home/](https://epcontables.github.io/home/)

## 🚀 Tecnologías y Herramientas
Este proyecto fue construido priorizando el rendimiento, la experiencia de usuario (UX) y despliegues estáticos rápidos:

- **HTML5 Semántico**
- **Tailwind CSS v3** — Estilos utilitarios. Compilado desde `input.css` a `output.css` con la CLI de Tailwind.
- **Tailwind CLI / PostCSS / Autoprefixer** — Dependencias de desarrollo usadas para generar el `output.css` (ver `package.json`).
- **Vue.js 3 (CDN)** — Pequeña reactividad para el menú móvil y notificaciones, cargada desde la CDN para evitar bundles.
- **AOS** — Animaciones al hacer scroll.
- **Font Awesome (subset: solid)** — Íconos cargados y optimizados para reducir CSS no usado.
- **Despliegue:** Netlify / Vercel (configuración de caché y headers en `netlify.toml` / `vercel.json`).

Nota: Para regenerar `output.css` localmente ejecutar:

```
npx tailwindcss -i ./input.css -o ./output.css --minify
```

Y para desarrollo con re-compilado automático:

```
npx tailwindcss -i ./input.css -o ./output.css --watch
```

## 👨‍💻 Equipo de Desarrollo
* Desarrollado y mantenido internamente por el equipo de Ep Contables.
