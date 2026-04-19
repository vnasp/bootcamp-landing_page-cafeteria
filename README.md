# Cafetería Agere

Proyecto desarrollado como desafío del **Bootcamp Frontend Developer de Talento Digital para Chile**. El objetivo era un landing page para una cafetería con diseño tipo bento box, usando cajas decorativas superpuestas con colores sólidos e imágenes de fondo.

> **Nota:** Este es un proyecto académico de maquetación, no un blog funcional.

## Tecnologías

- HTML5 semántico
- SCSS con arquitectura 7-1 y metodología BEM
- Flexbox para layout
- Font Awesome 6
- Google Fonts (PT Mono, Roboto Light)

## Estructura SCSS

```
assets/sass/
├── abstracts/    → Variables, mixins
├── base/         → Reset, tipografía
├── components/   → Botones, cajas decorativas
├── layout/       → Header, main, body
└── main.scss     → Punto de entrada
```

## Desarrollo local

```bash
# Compilar SCSS en modo watch
npm run sass
```
