En CSS, las propiedades definen los estilos específicos que se aplican a los elementos HTML en una página web. Existen numerosas propiedades, cada una diseñada para controlar aspectos distintos del diseño y la presentación. Aquí te presento una selección de las propiedades más comunes y utilizadas en CSS, especialmente enfocadas en textos, listas y tablas.

### **Propiedades Comunes de CSS**

#### **1. Propiedades de Texto**
- **`color`:** Especifica el color del texto.
  ```css
  p {
    color: #333;
  }
  ```
- **`font-family`:** Define la familia tipográfica para el texto.
  ```css
  body {
    font-family: Arial, sans-serif;
  }
  ```
- **`font-size`:** Controla el tamaño del texto.
  ```css
  h1 {
    font-size: 24px;
  }
  ```
- **`font-weight`:** Determina el grosor del texto.
  ```css
  strong {
    font-weight: bold;
  }
  ```
- **`text-align`:** Alinea el texto dentro de un elemento.
  ```css
  .center {
    text-align: center;
  }
  ```
- **`line-height`:** Establece la altura de línea del texto.
  ```css
  p {
    line-height: 1.5;
  }
  ```
- **`text-decoration`:** Agrega decoración al texto (como subrayado, tachado).
  ```css
  a {
    text-decoration: none;
  }
  ```
- **`letter-spacing`:** Ajusta el espaciado entre caracteres.
  ```css
  h1 {
    letter-spacing: 2px;
  }
  ```
- **`text-transform`:** Controla la capitalización de texto.
  ```css
  .uppercase {
    text-transform: uppercase;
  }
  ```

#### **2. Propiedades de Listas**
- **`list-style-type`:** Define el estilo de viñeta para listas desordenadas o el estilo de numeración para listas ordenadas.
  ```css
  ul {
    list-style-type: square;
  }
  ```
- **`list-style-position`:** Establece si la viñeta o número está dentro o fuera del flujo de contenido del elemento de lista.
  ```css
  ol {
    list-style-position: inside;
  }
  ```
- **`list-style-image`:** Utiliza una imagen como viñeta de la lista.
  ```css
  ul {
    list-style-image: url('bullet.png');
  }
  ```

#### **3. Propiedades de Tablas**
- **`border`:** Define el borde de las celdas, filas, o de toda la tabla.
  ```css
  table {
    border: 1px solid black;
  }
  ```
- **`border-collapse`:** Controla si los bordes de las celdas están separados o colapsados en uno solo.
  ```css
  table {
    border-collapse: collapse;
  }
  ```
- **`border-spacing`:** Ajusta el espacio entre los bordes de las celdas cuando `border-collapse` está en `separate`.
  ```css
  table {
    border-spacing: 5px;
  }
  ```
- **`padding`:** Aplica espacio entre el borde de la celda y su contenido.
  ```css
  td, th {
    padding: 10px;
  }
  ```
- **`text-align`:** Alinea el contenido de las celdas.
  ```css
  th {
    text-align: left;
  }
  ```

#### **4. Propiedades Comunes para Layout**
- **`width` y `height`:** Especifican el ancho y alto de un elemento.
  ```css
  .box {
    width: 100px;
    height: 100px;
  }
  ```
- **`margin`:** Controla el espacio externo alrededor de un elemento.
  ```css
  .container {
    margin: 20px;
  }
  ```
- **`padding`:** Ajusta el espacio interno dentro de un elemento.
  ```css
  .box {
    padding: 10px;
  }
  ```
- **`display`:** Determina el tipo de caja de un elemento (por ejemplo, `block`, `inline`, `flex`, `grid`).
  ```css
  .flex-container {
    display: flex;
  }
  ```
- **`position`:** Controla la posición de un elemento (por ejemplo, `static`, `relative`, `absolute`, `fixed`).
  ```css
  .sticky {
    position: fixed;
    top: 0;
  }
  ```

Estas propiedades permiten una gran variedad de diseños y estilos y son esenciales para cualquier diseñador o desarrollador web que busque crear interfaces atractivas y funcionales. Dominar estas propiedades es clave para implementar efectivamente cualquier diseño CSS.