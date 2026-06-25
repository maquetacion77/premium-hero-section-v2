# 🌟 Premium Hero Section (Estilo 02 - Terracota Minimal) - Instituto de Estética y Belleza

¡Bienvenido/a! Este repositorio presenta el **Estilo 02** para nuestra sección Hero interactiva avanzada. Siguiendo una arquitectura orientada a la reutilización, este proyecto demuestra cómo **un mismo esqueleto HTML y un único archivo JavaScript** pueden transformarse radicalmente de personalidad visual (de un look oscuro/azul corporativo a un diseño cálido, minimalista y translúcido) modificando exclusivamente la capa de estilos CSS (`hero02.css`).

El objetivo principal de esta variante fue explorar una estética de alto contraste terroso (`#d2691e`), transparencias modernas y un enfoque de navegación minimalista.

🌐 **Ver el proyecto en vivo (Estilo 02):** [Haz clic aquí para ver en GitHub Pages](https://maquetacion77.github.io/premium-hero-section/)  
🎨 **Caso de estudio visual:** [Ver presentación completa en Behance](TU_ENLACE_DE_BEHANCE_AQUÍ)

---

## 🛠️ Características Técnicas & Variantes de Arquitectura

Al mantener intacta la estructura HTML base y la lógica interactiva, este desarrollo pone a prueba la flexibilidad de los **estilos modulares (component-based CSS)**:

* **Filosofía "One HTML, Multiple Styles":** Demostración práctica de desacoplamiento de software. El archivo `index.html` y la lógica de `hero.js` son idénticos a su versión predecesora, permitiendo un intercambio de temas inmediato.
* **Enfoque Visual Minimalista (UI):** En esta variante, la botonera inferior oculta los elementos tipográficos e iconográficos en resoluciones de escritorio a través de CSS para priorizar un diseño limpio y una inmersión fotográfica absoluta.
* **Doble Capa de CSS Grid:** No solo la sección principal utiliza una matriz de 10x10, sino que los bloques `<article>` fueron transformados internamente en Grids independientes para alinear de forma milimétrica los títulos y los párrafos sobre fondos translúcidos.
* **CDN de Assets Propio:** Las imágenes de alta resolución son consumidas dinámicamente desde un repositorio centralizado en GitHub, optimizando la velocidad de transferencia de datos y garantizando la consistencia de los archivos en plataformas como CodePen y Behance.
* **Interactividad y Accesibilidad Consolidadas:** Se conserva el slider inteligente con Vanilla JavaScript (ES6+), los temporizadores autónomos (`autoplay`), y las directivas semánticas WCAG (`aria-label`) para lectores de pantalla.

---

## 📂 Estructura del Repositorio (Variante 02)

```text
├── index.html       # Estructura semántica base (Compartida/Reutilizada).
├── hero02.css       # Estilos temáticos cálidos, Grid interno de artículos y responsive.
└── hero.js          # Lógica del slider interactivo (Compartida/Reutilizada).
