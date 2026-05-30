# Portafolio Personal — Manuel Jordan

Portafolio personal desarrollado con Astro, Tailwind CSS y astro-icon.

## Stack

- [Astro](https://astro.build) — framework principal
- [Tailwind CSS v4](https://tailwindcss.com) — estilos
- [astro-icon](https://www.astroicon.dev) + `@iconify-json/mdi` — iconos

## Estructura

```text
/
├── public/
│   └── mj-logo.svg
├── src/
│   ├── components/
│   │   ├── Header.astro       # Nav fijo con scroll effect y active link
│   │   ├── NavIcon.astro      # Link de navegación con estado activo
│   │   ├── Inicio.astro       # Sección hero
│   │   ├── SobreMi.astro      # Sección about
│   │   ├── MiniSpan.astro     # Badge/chip reutilizable
│   │   └── LinkIcon.astro     # Link con icono (LinkedIn, GitHub)
│   ├── layouts/
│   │   └── Layout.astro       # Layout base con fondo de constelación animado
│   ├── pages/
│   │   └── index.astro        # Página principal (single-page)
│   └── styles/
│       └── global.css         # Variables CSS, tipografía responsive
└── package.json
```

## Comandos

| Comando       | Acción                                      |
| :------------ | :------------------------------------------ |
| `pnpm install` | Instala dependencias                       |
| `pnpm dev`     | Servidor local en `localhost:4321`         |
| `pnpm build`   | Build de producción en `./dist/`           |
| `pnpm preview` | Preview del build antes de desplegar       |