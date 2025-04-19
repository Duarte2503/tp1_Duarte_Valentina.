# TP1 – Curriculum Vitae en HTML5 y CSS

Alumna: Duarte Gutiérrez Valentina Ailén  
Carrera: Licenciatura en Diseño y Comunicación Visual  
Universidad: UNLa – Universidad Nacional de Lanús  
Año: 2025 – 



##  Descripción del trabajo

Este trabajo práctico consistió en la creación de un Curriculum Vitae digital utilizando HTML5, una hoja de estilos externa en CSS y diagramación con Flexbox. Se respetaron los lineamientos de estructura semántica y buenas prácticas de codificación.




##  Tecnologías y herramientas utilizadas

- HTML5 con etiquetas semánticas: <header>, <main>, <section>, <footer>, etc.
- CSS3: uso de selectores de clase, propiedades de tipografía, color, espaciado, bordes y fondo.
- Flexbox: aplicado en la estructura principal <main>, en la cabecera <header> y en el pie de página <footer> para lograr una distribución visual clara y flexible.
- Google Fonts: tipografías “Belleza” y “Montserrat”.
- Font Awesome: para íconos de redes sociales y contacto.
- Favicon personalizado: ícono propio en la pestaña del navegador.
- Inspección del navegador: herramienta usada para revisar y ajustar la disposición visual del sitio.



## Estructura y contenido

### Estructura general

Todo el contenido se encuentra dentro de un <div class="contenedor"> ubicado dentro del <body>, que actúa como bloque principal del diseño.

### Header

Contiene el nombre, subtítulo y una imagen personal. Está organizado con `flex-direction: row` para alinear el texto y la foto horizontalmente.

### Sección izquierda (información principal)

Ubicada dentro del <main>, esta sección contiene las partes más formales del CV:

- Datos personales
- Experiencia laboral
- Educación
- Idiomas
- Herramientas

Cada bloque se estructura mediante <section class="caja">.

### Sección derecha (perfil personal)

También dentro del <main>, agrupa la parte más subjetiva del perfil profesional:

- Sobre mí
- Habilidades
- Proyectos destacados

Estas están organizadas en <section class="otros">.

### Footer

Contiene información de contacto organizada en una lista no ordenada <ul>. Se usó Flexbox para distribuir íconos de forma horizontal, con clases de Font Awesome.



## Cambios realizados durante el proceso

### Corrección 1: Uso de `position: absolute` y falta de etiquetas semánticas

**Problemas señalados:**

- No se usaba Flexbox.
- Se usaban muchos <div> genéricos.
- Faltaban etiquetas semánticas como <main>, <section>, etc.

**Cambios realizados:**

- Uso correcto de etiquetas semánticas (header, main, section, footer, article, aside).
- Aplicación de Flexbox para organizar el contenido.
- Separación de contenido y estilo (uso de archivos .html y .css).
- Incorporación de íconos con Font Awesome en el footer mediante enlaces CDN.

### Corrección 2: Estructura semántica incorrecta en aside y article

**Problemas señalados:**

- Información importante ubicada dentro de aside y article en lugar de etiquetas como section.

**Cambios realizados:**

- Reorganización del contenido usando `section` para mayor coherencia estructural.

### Orden visual del header y uso de flex

**Problemas señalados:**

- Desorden en el header.
- La foto y el texto no estaban bien alineados.

**Cambios realizados:**

- Uso de flex-direction: row en el header.

### Footer mal estructurado

**Problemas señalados:**

- Mezcla de íconos e imágenes sin estructura clara.
- Uso de texto suelto en vez de listas.

**Cambios realizados:**

- Inclusión de listas (ul, li) en el footer.

### Clases innecesarias y código redundante

**Problemas señalados:**

- Clases como .encabezado innecesarias.
- Uso de propiedades CSS por defecto.

**Cambios realizados:**

- Eliminación de clases y propiedades CSS redundantes.
- Reorganización del código CSS.

### Corrección 3: Uso incorrecto de <strong> y dimensiones de imagen

**Problemas señalados:**

- No utilizar <strong> a menos que sea para destacar un texto especialmente importante dentro del html.  
- Falta de medidas en línea para la imagen del header.

**Cambios realizados:**

- Reemplazo de <strong> por <span> con clases.
- Agregado de dimensiones a la imagen directamente en el HTML.



## Datos técnicos

- Resolución base de diseño: 1920x1080 px
- Editor de código: Visual Studio Code
- Visualización verificada en: Google Chrome
- Herramientas de desarrollo: Inspector del navegador 




## Comentario personal

Me gustó ir mejorando el trabajo progresivamente y aplicar correcciones que surgieron en clase y en la devolución del profe. 

La devolución fue algo frustrante al principio, ya que hubo varios errores señalados, pero me ayudó muchísimo a detectar fallas en mi estructura. Gracias a eso pude mejorar aspectos importantes como el uso semántico de etiquetas y la organización visual.

Además, el uso del inspector del navegador me permitió ver con más claridad cómo se estaba comportando el diseño, aunque todavía me gustaría que se viera más prolijo a nivel Diseño e interactivo. Sé que con más práctica voy a poder lograr una mejor presentación tanto en estructura como en diseño.
