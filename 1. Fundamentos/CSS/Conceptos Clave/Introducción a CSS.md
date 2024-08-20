El **CSS (Cascading Style Sheets)** es un lenguaje de diseño utilizado para describir la presentación de un documento escrito en HTML o XML. Mientras que HTML estructura el contenido de una página web, CSS define cómo debe mostrarse visualmente, incluyendo colores, fuentes, espaciado, disposición y otras características estilísticas.

---

### **Introducción a CSS**

#### **1. ¿Qué es CSS?**
   - **Descripción:** CSS es un lenguaje que permite separar el contenido de la presentación en las páginas web. Se utiliza para controlar el estilo y el diseño de múltiples páginas web a la vez.
   - **Siglas:** CSS significa "Hojas de Estilo en Cascada", lo que implica que los estilos pueden aplicarse en un orden de prioridad que "cascada" desde un nivel más general a uno más específico.

#### **2. Cómo se Integra CSS en HTML**
   - **CSS Inline:** Se aplica directamente en los elementos HTML mediante el atributo `style`.
     - **Ejemplo:**
       ```html
       <p style="color: blue; font-size: 16px;">Este es un párrafo con estilo en línea.</p>
       ```
   - **CSS Interno:** Se define dentro de la misma página HTML en el elemento `<style>` dentro de la sección `<head>`.
     - **Ejemplo:**
       ```html
       <head>
           <style>
               p {
                   color: blue;
                   font-size: 16px;
               }
           </style>
       </head>
       <body>
           <p>Este es un párrafo con estilo interno.</p>
       </body>
       ```
   - **CSS Externo:** Se enlaza a un archivo CSS separado usando la etiqueta `<link>` en la sección `<head>`.
     - **Ejemplo:**
       ```html
       <head>
           <link rel="stylesheet" href="styles.css">
       </head>
       <body>
           <p>Este es un párrafo con estilo externo.</p>
       </body>
       ```
       - **Archivo styles.css:**
         ```css
         p {
             color: blue;
             font-size: 16px;
         }
         ```

#### **3. [[Selectores de CSS]]**
   - **Selectores Básicos:** Permiten seleccionar elementos HTML para aplicarles estilos.
     - **Selector de Tipo:** Selecciona todos los elementos de un tipo específico. Ejemplo: `p { ... }` aplica estilos a todos los párrafos.
     - **Selector de Clase:** Selecciona elementos que tienen un atributo `class` específico. Ejemplo: `.highlight { ... }` aplica estilos a todos los elementos con `class="highlight"`.
     - **Selector de ID:** Selecciona un elemento único con un atributo `id` específico. Ejemplo: `#header { ... }` aplica estilos al elemento con `id="header"`.
   - **Selectores Avanzados:** Permiten seleccionar elementos basados en combinaciones o condiciones específicas.
     - **Selector de Descendiente:** Selecciona elementos que son descendientes de otro elemento. Ejemplo: `div p { ... }` selecciona todos los párrafos dentro de `div`.
     - **Pseudo-clases:** Aplican estilos a un estado particular de un elemento. Ejemplo: `a:hover { ... }` aplica estilos cuando el ratón pasa sobre un enlace.

#### **4. [[Propiedades de CSS]]**
   - **Color y Fondo:**
     - **color:** Define el color del texto. Ejemplo: `color: red;`.
     - **background-color:** Define el color de fondo de un elemento. Ejemplo: `background-color: yellow;`.
   - **Tipografía:**
     - **font-family:** Especifica la fuente del texto. Ejemplo: `font-family: Arial, sans-serif;`.
     - **font-size:** Define el tamaño de la fuente. Ejemplo: `font-size: 14px;`.
   - **Margen y Relleno:**
     - **margin:** Define el espacio exterior alrededor de un elemento. Ejemplo: `margin: 20px;`.
     - **padding:** Define el espacio interior entre el contenido de un elemento y su borde. Ejemplo: `padding: 10px;`.
   - **Bordes:**
     - **border:** Define el borde alrededor de un elemento. Ejemplo: `border: 1px solid black;`.

#### **5. [[La Cascada y la Herencia en CSS]]**
   - **Cascada:** La "C" en CSS significa "Cascading" (Cascada), lo que implica que los estilos pueden superponerse según su orden de especificidad y origen.
     - **Orden de Prioridad:** Si un elemento tiene múltiples reglas CSS aplicadas, se da prioridad al estilo más específico y al que se encuentra más abajo en la cascada.
   - **Herencia:** Algunas propiedades en CSS, como el color del texto y la tipografía, se heredan de los elementos padre a los elementos hijo.
     - **Ejemplo:**
       ```css
       body {
           font-family: Arial, sans-serif;
           color: black;
       }
       p {
           font-size: 16px;
       }
       ```
       En este caso, todos los párrafos heredarán la fuente y el color del cuerpo del documento, pero tendrán un tamaño de fuente específico.

#### **6. Buenas Prácticas**
   - **Uso de CSS Externo:** Mantén los estilos separados del contenido HTML para mejorar la mantenibilidad y la reutilización.
   - **Organización de Selectores:** Agrupa los selectores relacionados y utiliza comentarios para facilitar la lectura y el mantenimiento del código CSS.
   - **Uso de Clases sobre IDs:** Utiliza clases en lugar de IDs para aplicar estilos que se repetirán en varios elementos, ya que las clases son más flexibles y menos específicas que los IDs.

---

Esta introducción a CSS proporciona una base sólida para comprender cómo estilizar páginas web de manera efectiva, permitiendo a los desarrolladores crear diseños atractivos, consistentes y fáciles de mantener.