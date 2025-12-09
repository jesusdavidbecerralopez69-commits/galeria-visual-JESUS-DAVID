# galeria-visual-JESUS-DAVID
# 🖼️ galeria-visual-<tu_nombre>

## 🚀 Breve Descripción del Proyecto

Este proyecto es una **Galería Visual Estática** desarrollada como la actividad de transferencia final del módulo de imágenes en CSS.

El objetivo principal fue consolidar y aplicar propiedades visuales avanzadas de CSS, incluyendo **Variables CSS**, **Gradientes**, **Imágenes de Fondo con configuración avanzada** y **Transparencias (RGBA)**, para construir una interfaz web estática, atractiva y profesional.

El diseño se enfoca en la **accesibilidad** y la **legibilidad**, utilizando un tema oscuro y un alto contraste, y se construyó siguiendo buenas prácticas de documentación.

---

## 🛠️ Estructura y Tecnologías

* **HTML5:** Estructura semántica (`<header>`, `<main>`, `<figure>`, `<figcaption>`).
* **CSS3:** Estilización completa, incluyendo:
    * Variables CSS (`:root`) para la paleta de colores.
    * CSS Grid para la disposición de la galería.
    * `linear-gradient` y `radial-gradient`.
    * `background-size`, `background-position`, `background-repeat`.
    * `rgba()` para transparencia.

### 📁 Estructura del Repositorio
## 💻 Instrucciones para Visualización Local

Para ver el proyecto en tu máquina local, sigue estos sencillos pasos:

1.  **Clonar el Repositorio:** Abre tu terminal o Git Bash y ejecuta:
    ```bash
    git clone [https://github.com/](https://github.com/)<tu_usuario>/galeria-visual-<tu_nombre>.git
    ```
2.  **Navegar a la Carpeta:**
    ```bash
    cd galeria-visual-<tu_nombre>
    ```
3.  **Abrir el Archivo:** Simplemente haz doble clic en el archivo `index.html`. El sitio se abrirá automáticamente en tu navegador predeterminado.

---

## 🌐 Enlace a GitHub Pages

La galería ha sido publicada como un sitio estático utilizando GitHub Pages.

* **URL Pública:** `<Pega aquí la URL final de tu GitHub Pages, por ejemplo: https://tu_usuario.github.io/galeria-visual-tu_nombre/>`

---

## 💡 Decisiones de Diseño (Requisito de Documentación)

Se eligieron las siguientes propiedades y estilos para lograr una interfaz profesional y cumplir con los requisitos técnicos:

### 1. Paleta de Colores (`:root` Variables)

* **Elección:** Se utilizó un tema **Oscuro** con una base de color **Cian profundo (`#00ADB5`)** como acento principal.
* **Propósito:**
    * El fondo oscuro (`--color-fondo-principal: #222831`) reduce la fatiga visual.
    * El acento Cian (`--color-primario`) fue elegido por su asociación con la **innovación y la tecnología**, proyectando una imagen de **profesionalismo**.
    * Se aseguró un **Contraste Suficiente** (Texto claro sobre fondo oscuro) en todos los elementos para mantener la legibilidad, tal como lo requiere la actividad.

### 2. Diseño de Gradientes

* **Gradiente 1 (Encabezado):** Se aplicó un gradiente lineal (`linear-gradient(135deg, ...)`) que va desde el color de fondo a un tono de fondo ligeramente más oscuro.
    * **Propósito:** Dar una sensación de **profundidad y sutileza** al encabezado en lugar de un color sólido, manteniendo la sobriedad.
* **Gradiente 2 (Banner Overlay):** Se usó un gradiente radial (`radial-gradient(circle, ...)`) con tonos oscuros dentro de la capa de transparencia.
    * **Propósito:** Este gradiente ayuda a **enfocar la atención** en el centro del texto del banner, haciendo que el texto sea aún más legible en el centro.

### 3. Uso de `background-image` y Transparencias

* **Configuración de Background:** En la sección `.banner-promocion`, se usó `background-size: cover`, `background-position: center center` y `background-repeat: no-repeat`.
    * **Propósito:** Esto garantiza que la imagen de fondo cubra el banner de manera estética sin distorsionarse, independientemente del tamaño de la pantalla.
* **Transparencia (RGBA):** Se empleó `background-color: var(--color-transparencia-oscura);` (utilizando `rgba(0, 0, 0, 0.75)`).
    * **Propósito:** Esta capa **semitransparente** sobre la imagen de fondo asegura que el texto (títulos y descripciones) permanezca **perfectamente legible**, cumpliendo directamente con el requisito de accesibilidad.

### 4. Optimización de Imágenes

*(Si optimizaste las imágenes (e.g., con TinyPNG, Compressor.io, o ajustando formatos), describe el proceso aquí. Si no lo hiciste, puedes mencionar:)*
* *Mantenibilidad: Se utilizaron principalmente el formato **WebP** (`.webp`) para asegurar un tiempo de carga rápido y mantener la calidad visual de los recursos gráficos.*

---

## ⏰ Duración y Evaluación

* **Duración Estimada de la Actividad:** 2 horas y 45 minutos.
* **Evidencia de Aprendizaje:** Repositorio público con el código final y la URL de GitHub Pages.# pseudoclases
