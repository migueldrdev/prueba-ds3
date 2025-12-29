# Prueba Técnica DS3 - Modernización de Ficha de Producto

Este repositorio contiene la solución propuesta para la modernización de la ficha del producto **AMP 6-1427200-4**, enfocada en rendimiento, SEO y experiencia móvil (Mobile First).

## 🚀 Mejoras Implementadas

### 1. Arquitectura y Código
- **HTML5 Semántico:** Se reemplazó la estructura antigua basada en tablas y divs genéricos por etiquetas semánticas (`<main>`, `<aside>`, `<nav>`) para mejorar la accesibilidad y lectura de buscadores.
- **Renderizado Dinámico:** Se implementó una lógica en JavaScript (Vanilla) que simula la carga de datos (Marcas, Listas de Precios y Productos Relacionados) desde objetos JSON. Esto facilita la futura integración con una API o Base de Datos.

### 2. Diseño Responsive (Mobile First)
- **Layout Adaptativo:**
    - **Escritorio:** Diseño de 3 columnas para maximizar el uso del espacio y la visibilidad del catálogo completo.
    - **Móvil:** Diseño de columna única con un **Drawer de Navegación (Menú Lateral)** para mantener accesibles las marcas y listas de precios sin saturar la pantalla.
- **Galería Interactiva:** Carrusel de imágenes funcional sin dependencias pesadas.

### 3. SEO Técnico
- **Schema.org (JSON-LD):** Se añadieron datos estructurados de `Product` para que Google pueda indexar precio, stock y SKU directamente en los resultados de búsqueda.
- **Metaetiquetas:** Configuración correcta de viewport y metadatos para redes sociales.

## 🛠️ Tecnologías
- HTML5
- Tailwind CSS (vía CDN para demostración)
- JavaScript (ES6+)

## 🔗 Demo
Puedes ver el resultado final funcionando aquí: https://migueldrdev.github.io/prueba-ds3/6-1427200-4.html
