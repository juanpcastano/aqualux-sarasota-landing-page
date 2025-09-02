# Aqualux Sarasota Landing Page

Landing page desarrollada con [Astro](https://astro.build/) y TailwindCSS para Aqualux Sarasota.

## Características
- Diseño responsivo y moderno
- Animaciones personalizadas
- Fuentes personalizadas
- Imágenes optimizadas
- Componentes reutilizables

## Estructura del proyecto
```
astro.config.mjs
package.json
pnpm-lock.yaml
README.md
tsconfig.json
public/
  hero.webp
  logo.ico
  fonts/
    bebas-neue-v15-latin-regular.woff2
    source-sans-3-v18-latin-800.woff2
    source-sans-3-v18-latin-regular.woff2
src/
  assets/
    astro.svg
    background.svg
  components/
    Footer.astro
    Header.astro
    Hero.astro
    Logo Contact.astro
    Logo.astro
  images/
    HeroImage.png
    HeroImageNoText.png
    logo.ico
  layouts/
    First Section.astro
    Layout.astro
  pages/
    index.astro
  styles/
    global.css
```

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/juanpcastano/aqualux-sarasota-landing-page.git
   cd aqualux-sarasota-landing-page
   ```
2. Instala las dependencias:
   ```bash
   pnpm install
   ```
3. Inicia el servidor de desarrollo:
   ```bash
   pnpm run dev
   ```

## Personalización
- Modifica los componentes en `src/components/` para cambiar el contenido.
- Cambia las imágenes en `src/images/` y `public/`.
- Edita los estilos globales en `src/styles/global.css`.

## Despliegue
Puedes desplegar el sitio en plataformas como Vercel, Netlify o tu propio servidor.

## Créditos
- [Astro](https://astro.build/)
- [TailwindCSS](https://tailwindcss.com/)

---
Aqualux Sarasota © 2025
