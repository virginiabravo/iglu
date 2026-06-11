# Tarea 03: Pieza Narrativa Individual en HTML
**Proyecto Grupal:** Especies al Límite

## 🔗 Link al sitio
[Las especies amenazadas que sí vemos y las que ignoramos](https://virginiabravo.github.io/p-gina-web/)



## Comentarios sobre el proceso de desarrollo y diseño HTML

Para estructurar esta página web utilicé etiquetas de HTML e integré la identidad visual del proyecto grupal directamente mediante estilos internos (`<style>`).

### 1. Estructura Semántica base
Organicé la crónica periodística dividiendo el contenido lógicamente:
* Utilicé `<header>` para el título principal (`<h1>`) y la introducción.
* Agrupé todo el cuerpo del reportaje en la etiqueta `<main>`, separando las distintas secciones analíticas con subtítulos (`<h2>`) y ordenando la lectura mediante párrafos (`<p>`).
* Finalmente, cerré la página con un `<footer>` para alojar los créditos y las herramientas utilizadas.

### 2. Integración de la Identidad Visual
Para que la pieza individual conversara visualmente con la webstory grupal, importé las fuentes oficiales desde Google Fonts (**Capriola** para encabezados y **Lora** para el cuerpo de texto) y apliqué la paleta de colores del manual:
* El fondo utiliza el tono crema (`#FBF8F0`) y el texto principal el azul profundo (`#1F3D5B`) para asegurar contraste y legibilidad.
* Agregué una línea divisoria (`<hr>`) debajo del título y le asigné el color borgoña (`#86223E`), estipulado para los destacados internos, separando claramente la cabecera del inicio de la lectura.

### 3. Formato del texto periodístico
Para darle un aspecto formal de crónica, apliqué justificado (`text-align: justify;`) a todos los párrafos. Además, utilicé la etiqueta `<strong>` (vinculada al color borgoña de la identidad visual grupal) para resaltar datos numéricos impactantes (como las *9.259 visitas* de la chinchilla) y conceptos teóricos clave (como *"termómetro cultural"* o *"extinción virtual"*). Esto ayuda a guiar el escaneo visual del lector hacia los hallazgos principales.

### 4. Inserción y ajuste de la Visualización
Uno de los mayores retos fue la carga del gráfico (`vis_02.jpg`). Tuve que utilizar **rutas relativas** asegurándome de que la imagen y el archivo `index.html` estuvieran en la misma carpeta del repositorio para que no apareciera rota en GitHub Pages. 
Para evitar que el tamaño original de la imagen rompiera los márgenes y generara *scroll* horizontal, le asigné un `width: 100%`, envolviéndola en un contenedor con un fondo amarillo pálido (`#EFEDA0`) que la resalta del resto de la página y combina con las crónicas de mis compañeras.

### 5. Uso de Enlaces Externos
Implementé la etiqueta `<a>` (con el atributo `target="_blank"` para que abran en una nueva pestaña) tanto en el texto narrativo como en el pie de página. Vincular fuentes como la *Lista Roja de la UICN* y *Wikipedia Pageviews* que le otorga respaldo científico y credibilidad a los datos de la crónica.