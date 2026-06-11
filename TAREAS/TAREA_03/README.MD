# Tarea 03: Pieza Narrativa Individual en HTML
**Proyecto Grupal:** Especies al Límite

## 🔗 Link al sitio
[Las especies amenazadas que sí vemos y las que ignoramos](https://virginiabravo.github.io/p-gina-web/)



## Comentarios sobre el proceso de armado HTML

Para estructurar esta página web, me enfoqué en usar las etiquetas de forma que la crónica fuera fácil de leer, cumpliendo con la regla de mantener un código simple.

* **Estructura base:** Utilicé `<header>` para el título principal (`<h1>`) y `<footer>` para los créditos finales. Todo el cuerpo de la crónica lo agrupé dentro de una etiqueta `<div>` separando los temas con subtítulos (`<h2>`) y párrafos (`<p>`).

* **Formato del texto (Justificado y Negritas):** Para darle un aspecto formal, le agregué un estilo en línea al contenedor principal (`style="text-align: justify;"`) para que los márgenes quedaran rectos. Además, utilicé la etiqueta `<strong>` para destacar en negrita conceptos clave (como *"termómetro cultural"* o *"extinción virtual"*) y los datos numéricos más impactantes (como las *9.259 visitas* de la chinchilla). Esto ayuda a guiar la vista del lector hacia los hallazgos principales.

* **Ajuste de la imagen:** Al integrar la visualización del gráfico (`vis_02.jpg`) con la etiqueta `<img>`, me di cuenta de que su tamaño original rompía los márgenes de la página y generaba un molesto *scroll* horizontal. Lo solucioné agregándole el atributo `width="100%"`, lo que permite que el gráfico se adapte automáticamente a cualquier tamaño de pantalla.

* **Elección de Enlaces:** Utilicé la etiqueta `<a>` (con el atributo `target="_blank"` para que abran en otra pestaña) dentro de la narrativa y en el pie de página. Elegí enlazar la *Lista Roja de la UICN* y la herramienta *Wikipedia Pageviews Analysis* ya que son las fuentes reales que respaldan la historia de la chinchilla y le dan credibilidad a los datos de la crónica.