# Primera Parte

## Pregunta 1. Sobre listas y enlaces

**1.1** ¿En qué consiste el efecto de "faux columns" o columnas falsas? Pon un ejemplo propio de su utilización.
El efecto de "faux columns" simula columnas de igual altura usando un fondo compartido.
<div class="container" style="display: flex; background: linear-gradient(to right, #ddd 50%, #ccc 50%);">
    <div style="width: 50%; padding: 20px;">Columna 1</div>
    <div style="width: 50%; padding: 20px;">Columna 2</div>
</div>

**1.2** ¿Cuáles son los cinco estados de los enlaces? Crea un ejemplo con HTML y CSS en el que se aprecie el funcionamiento de cada uno de ellos.
Cinco estados: link, visited, hover, active, focus.
<a href="#" style="color: blue;">Link sin visitar</a>
<style>
    a:visited { color: purple; }
    a:hover { color: green; }
    a:active { color: red; }
    a:focus { outline: 1px solid orange; }
</style>


**1.3** Pon un ejemplo propio de correcta utilización de cada uno de los tipos de lista, explicando por qué es el tipo más adecuado en cada caso.
Ordenada <ol>: Para pasos secuenciales.
<ol><li>Paso 1</li><li>Paso 2</li></ol>
No ordenada <ul>: Para elementos sin orden específico.
<ul><li>Elemento A</li><li>Elemento B</li></ul>
De definición <dl>: Para pares de términos y definiciones.
<dl><dt>HTML</dt><dd>Lenguaje de marcado</dd></dl>

## Pregunta 2. Sobre el modelo de cajas

**2.1** ¿En qué propiedad/es del modelo de cajas se pueden aplicar valores negativos? Pon un ejemplo en el que tenga sentido hacerlo.
Propiedades como margin y top admiten valores negativos para ajustar el posicionamiento.
<div style="width: 100px; margin-left: -20px;">Caja desplazada</div>

**2.2** ¿Para qué sirven las propiedades `min-width`, `max-width`, `min-height` y `max-height`? Pon un ejemplo propio de su utilización.
Establecen límites de tamaño de un elemento.
<div style="min-width: 100px; max-width: 300px;">Límites de ancho</div>

**2.3** Describe el funcionamiento de la propiedad `overflow` y sus posibles valores. Investiga posibles usos de interés de esta propiedad.
Controla el contenido que se sale del contenedor:
visible, hidden, scroll, auto.
<div style="width: 100px; height: 50px; overflow: auto;">Texto largo...</div>

## Pregunta 3. Sobre Accesibilidad

**3.1** ¿En qué consiste el Quirks mode? ¿De qué forma hay que tenerlo en cuenta al diseñar nuestras páginas?
Es un modo de compatibilidad para navegadores antiguos. Para evitarlo, usa <!DOCTYPE html>.

**3.2** ¿Cuáles son las principales características que debe tener una página web para ser accesible? Pon ejemplos de cada una de ellas.
Texto alternativo: <img src="imagen.jpg" alt="Descripción">

Contraste adecuado: Facilita la lectura.

Etiquetas semánticas: Para estructurar contenido. <main>Contenido principal</main>

Roles ARIA.<button aria-label="Cerrar">X</button>
