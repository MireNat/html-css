# Ejercicio Guiado: Website para David Chu's China Bistro

## Descripción
Este proyecto es un sitio web responsive para el restaurante "David Chu's China Bistro", desarrollado como parte del ejercicio guiado del Módulo 1: Fundamentos de Desarrollo FullStack de la Maestría FullStack Development. El sitio web presenta un diseño atractivo y funcional que se adapta a diferentes tamaños de pantalla, desde dispositivos móviles hasta computadoras de escritorio.

## Características
- **Diseño Responsive**: Adaptación completa a múltiples dispositivos mediante media queries
- **Navegación Intuitiva**: Menú de navegación claro con transformación a "hamburguesa" en dispositivos móviles
- **Secciones Principales**: Header, Jumbotron, Mosaicos (Menú, Especiales, Mapa) y Footer
- **Integración de Google Maps**: Visualización de la ubicación del restaurante
- **Estética Atractiva**: Uso de paleta de colores coherente y tipografía personalizada

## Tecnologías Utilizadas
- HTML5
- CSS3
- Bootstrap (Framework CSS)
- jQuery (para funcionalidades interactivas)
- Google Fonts (Oxygen y Lora)

## Estructura del Proyecto
```
david-chu-bistro/
├── css/
│   ├── bootstrap.min.css
│   └── styles.css
├── js/
│   ├── jquery-2.1.4.min.js
│   ├── bootstrap.min.js
│   └── script.js
├── images/
│   ├── restaurant-logo_large.png
│   ├── restaurant-logo_medium.png
│   ├── jumbotron_1200.jpg
│   ├── jumbotron_992.jpg
│   ├── jumbotron_768.jpg
│   ├── menu-tile.jpg
│   ├── specials-tile.jpg
│   └── star-k-logo.png
├── index.html
├── menu-categories.html
├── single-category.html
└── README.md
```

## Implementación
El sitio implementa un diseño responsive utilizando el sistema de grid de Bootstrap y media queries personalizadas para cinco rangos de tamaño de pantalla:
- Dispositivos grandes (≥1200px)
- Dispositivos medianos (992px-1199px)
- Dispositivos pequeños (768px-991px)
- Dispositivos extra pequeños (<767px)
- Dispositivos súper pequeños (<479px)

## Cómo Ver el Sitio
1. Clonar este repositorio
2. Abrir el archivo `index.html` en cualquier navegador moderno
3. Alternativamente, visitar la versión en vivo: [David Chu's China Bistro](https://tu-usuario.github.io/david-chu-bistro)

## Aspectos Destacados del Código
- Implementación de efectos hover para mejorar la interactividad
- Uso estratégico de clases de visibilidad para optimizar la experiencia en diferentes dispositivos
- Estructuración semántica del HTML para mejorar la accesibilidad y SEO
- Organización modular del CSS para facilitar mantenimiento

## Autor
Mireya Huanca

---
*Este proyecto fue desarrollado con fines educativos como parte de la Maestría FullStack Development.*
