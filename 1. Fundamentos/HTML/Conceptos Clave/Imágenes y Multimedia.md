#### **1. Uso de Imágenes**

- **Elemento `<img>`:**
    - **Descripción:** Utilizado para incrustar imágenes en la página.
    - **Atributos Esenciales:**
        - `src`: Especifica la ruta de la imagen.
        - `alt`: Texto alternativo que describe la imagen, crucial para la accesibilidad y el [[SEO]].
    - **Ejemplo Completo:**
        ```html
        <img
	        src="paisaje.jpg"
	        alt="Vista de un paisaje natural con montañas al fondo"
	        title="Paisaje Natural">			
        ```

#### **2. Imágenes Responsivas**

- **Uso de `srcset` y `sizes`:**
    - **Descripción:** Permite al navegador seleccionar la imagen adecuada según el tamaño de pantalla y la densidad de píxeles.
    - **Ejemplo Completo:**
		```html
        <img src="flores.jpg" alt="Flores coloridas en campo"
     srcset="flores-480w.jpg 480w, flores-800w.jpg 800w, flores-1600w.jpg 1600w"
     sizes="(max-width: 600px) 480px, (max-width: 1200px) 800px, 1600px">
        ```

#### **3. Formatos de Imagen**

- **Descripción y Uso:**
    - **JPEG:** Mejor para fotografías.
    - **PNG:** Ideal para imágenes con transparencias.
    - **SVG:** Para gráficos vectoriales como logos e íconos.
    - **WebP:** Proporciona una compresión superior para imágenes sin perder calidad.

#### **4. Elementos de Video y Audio**

- **Video:**
    - **Elemento `<video>`:** Incorpora contenido de video.
    - **Atributos Comunes:** `controls`, `autoplay`, `loop`, `muted`.
    - **Ejemplo Completo:**
        ```html
        <video controls width="250">
		    <source src="clip.mp4" type="video/mp4">
		    <source src="clip.webm" type="video/webm">
		    Lo sentimos, tu navegador no soporta videos embebidos.
		</video>
        ```
- **Audio:**
    - **Elemento `<audio>`:** Usado para incluir sonido o música.
    - **Atributos Comunes:** `controls`, `autoplay`, `loop`.
    - **Ejemplo Completo:**
        ```html
        <audio controls>
		    <source src="musica.mp3" type="audio/mpeg">
		    <source src="musica.ogg" type="audio/ogg">
		    Tu navegador no soporta el elemento de audio.
		</audio>
        ```

#### **5. Buenas Prácticas**

- **Optimización de Recursos:** Comprimir imágenes y videos para acelerar tiempos de carga sin comprometer la calidad visual.
- **Accesibilidad:** Asegurar que todo contenido multimedia tenga alternativas de texto, subtítulos para videos, y descripciones de audio cuando sea necesario.
- **Autoplay Consciente:** Evitar el uso de `autoplay` con sonido para no perturbar al usuario, si se usa, asegurar que el contenido esté en mute por defecto.