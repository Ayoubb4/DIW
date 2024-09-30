# Primera parte de la práctica

## Pregunta 1

**Explica cuál es la función del lenguaje HTML y del lenguaje CSS en la creación de una página web.**

- **HTML (HyperText Markup Language)**: Es el lenguaje de marcado utilizado para estructurar el contenido de una página web. Define los diferentes elementos como párrafos, encabezados, imágenes, enlaces, listas, etc. HTML proporciona la estructura básica de una página web.
- **CSS (Cascading Style Sheets)**: Es un lenguaje que se utiliza para diseñar y dar formato a la apariencia visual de una página web. CSS controla el estilo de la página, es decir, el color de fondo, las fuentes, el espaciado, el diseño de las columnas.

**¿Por qué se recomienda el uso de los dos lenguajes? Di al menos 3 ventajas si lo usamos.**

1. **Separación de contenido y presentación**: Permite mantener el contenido (HTML) separado de la presentación (CSS), lo que facilita el mantenimiento.
2. **Mejora del rendimiento**: Al separar CSS en archivos externos, las páginas se cargan más rápido, ya que el CSS puede ser almacenado en caché.
3. **Mejor accesibilidad y SEO**: Un HTML semántico bien estructurado ayuda a los motores de búsqueda y dispositivos de asistencia a interpretar mejor la página.

**¿Es recomendable usar estilos CSS incrustados en el código HTML, o dentro de la página HTML? ¿Por qué?**

No se recomienda utilizar estilos CSS incrustados directamente en el código HTML (usando la etiqueta `<style>` dentro del archivo HTML o los estilos en línea con el atributo `style`). La mejor práctica es tener el CSS en un archivo externo para mantener el código más limpio, fácil de mantener y para mejorar el rendimiento de la página.

---

## Pregunta 2

 A partir del siguiente fragmento de código HTML:
  <p class="cursiva" id="verde">Texto</p>
  
  Indica el nombre de las partes y describe su función.
  <p> (etiqueta HTML): Esta es la etiqueta que define un párrafo en HTML. Indica al navegador que el texto dentro de esta etiqueta debe presentarse como un parrafo.
  
  class="cursiva" (atributo de clase): El atributo class asigna una clase CSS a este elemento. En este caso, el nombre de la clase es "cursiva".
  
  id="verde" (atributo de identificación): El atributo id asigna un identificador único a este elemento. El valor de este id es "verde". A diferencia de las clases, los id son únicos y se utilizan para identificar un solo elemento en la página.
  
  Texto (contenido): Este es el contenido de texto que se muestra dentro del párrafo. Aquí, simplemente es la palabra "Texto", pero puede ser cualquier contenido.


 ## Pregunta 3

**Explica la diferencia entre elementos en bloque y elementos en línea.**

- **Elementos en bloque:**
  - Ocupan todo el ancho disponible de su contenedor, comenzando en una nueva línea.
  - A menudo se utilizan para organizar grandes porciones de contenido.
  - Aceptan otros elementos en bloque y en línea como hijos.
  - **Ejemplos:** `<p>`, `<div>`, `<h1>`, `<section>`.

- **Elementos en línea:**
  - Solo ocupan el espacio necesario para su contenido y no obligan al resto de los elementos a comenzar en una nueva línea.
  - Generalmente contienen texto o pequeños fragmentos de contenido.
  - No pueden contener elementos en bloque dentro de ellos.
  - **Ejemplos:** `<span>`, `<a>`, `<em>`, `<strong>`.

A continuación, describe los siguientes elementos HTML y especifica si son en bloque o en línea:

- **p** - bloque
- **span** - en línea
- **h2** - bloque
- **cite** - en línea
- **q** - en línea
- **header** - bloque

## Pregunta 4

Explica qué es una regla de estilo y de qué elementos está formada. Pon un ejemplo indicando el nombre de cada elemento.

  • Una regla de estilo es un conjunto de directrices en CSS que define cómo se deben presentar los elementos de una página web. Cada regla aplica un conjunto de propiedades a uno o varios elementos HTML que coinciden con el selector especificado.

  • Elementos de una regla de estilo:
Selector: Indica qué elementos HTML serán afectados por la regla de estilo.
Propiedad: Define el aspecto que se va a modificar (color, tamaño, margen).
Valor: Especifica el valor que la propiedad debe tomar.

Ejemplo:
  p {
    color: blue;
    font-size: 16px;
  }

 # Pregunta 5

Utiliza Codepen ( codepen.io ) o Cssdeck ( cssdeck.com ) para hacer las pruebas y la captura de imagen del resultado.
Aquí ´tienes la lista de selectores:
•h1+p
•p > em
•p em
•p:lang(en)

