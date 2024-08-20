#### **1. DOCTYPE**

- **Descripción:** La declaración `<!DOCTYPE>` indica al navegador la versión de HTML que se está utilizando. Para HTML5, la declaración es simplemente `<!DOCTYPE html>`.
- **Propósito:** Asegura que el navegador interprete el documento de manera correcta y consistente, evitando modos de compatibilidad que podrían afectar el diseño y comportamiento de la página.

#### **2. Elemento `<html>`**

- **Descripción:** El elemento `<html>` envuelve todo el contenido de la página. Es la raíz del documento HTML.
- **Atributos Importantes:**
    - `lang`: Especifica el idioma del documento, como `<html lang="es">` para español. Esto es importante para la accesibilidad y los motores de búsqueda.

#### **3. Elemento `<head>`**

- **Descripción:** Contiene metadatos y enlaces que no son visualizados directamente en la página pero son esenciales para su funcionamiento y presentación.
- **Componentes Principales:**
    - **`<title>`:** Define el título de la página, que aparece en la pestaña del navegador y es crucial para [[SEO]] y usabilidad.
    - **`<meta>`:** Incluye metadatos como la codificación de caracteres (`<meta charset="utf-8">`), compatibilidad con dispositivos móviles (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`), y descripciones [[SEO]].
    - **`<link>`:** Utilizado para vincular hojas de estilo externas, íconos de pestaña, y otros archivos externos.
    - **`<script>`:** Para incluir scripts de JavaScript, ya sea internos o externos.
    - **`<style>`:** Permite escribir CSS directamente dentro del documento HTML.

#### **4. Elemento `<body>`**

- **Descripción:** Encapsula todo el contenido visible de la página como texto, imágenes, enlaces, formularios, y más.
- **Ejemplos de Elementos Internos:**
    - **Elementos de texto:** `<h1>`, `<p>`, `<a>`.
    - **Imágenes y multimedia:** `<img>`, `<video>`.
    - **Formularios:** `<form>`, `<input>`, `<label>`.
- **Propósito:** Es la sección donde se crea la mayor parte del contenido interactivo y visual que los usuarios experimentan directamente.

#### **Ejemplo de Estructura Básica en HTML5:**

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8">
    <title>Título de la Página</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>
<body>
    <header>
        <h1>Encabezado Principal</h1>
    </header>
    <nav>
        <!-- Barra de navegación aquí -->
    </nav>
    <main>
        <section>
            <h2>Subtítulo de Sección</h2>
            <p>Contenido principal...</p>
        </section>
    </main>
    <footer>
        <p>Derechos reservados © 2024</p>
    </footer>
</body>
</html>

```

---

Este esquema no solo es esencial para el correcto funcionamiento de una página web, sino que también facilita la accesibilidad, mejora el [[SEO]] y proporciona una estructura clara para el desarrollo y mantenimiento del sitio.