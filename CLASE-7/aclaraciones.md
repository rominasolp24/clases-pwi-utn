
En HTML y CSS, los elementos tienen diferentes comportamientos de visualización por defecto, que se pueden modificar utilizando las propiedades display. Los más comunes son inline, block e inline-block.

1. #Inline
Los elementos inline se muestran en línea con el texto circundante, ocupando solo el espacio necesario para su contenido. No inician una nueva línea y se pueden colocar junto a otros elementos inline.

Ejemplos de elementos inline son <span>, <a>, <strong>, etc.

#Características:

No comienzan en una nueva línea.
Solo ocupan el ancho necesario.
Ignoran las propiedades de ancho (width) y alto (height).
Respetan el padding horizontal, pero el padding vertical no afecta el flujo del documento.

Ejemplo:
<p>Este es un <span style="color: red;">texto en línea</span> dentro de un párrafo.</p>

2. #Block
Los elementos block se muestran como bloques. Ocupan todo el ancho disponible de su contenedor padre, iniciando una nueva línea antes y después de ellos.

Ejemplos de elementos block son <div>, <p>, <h1>, <ul>, etc.

#Características:

Comienzan en una nueva línea.
Ocupan todo el ancho disponible de su contenedor.
Respetan las propiedades de ancho (width) y alto (height).
Permiten todas las propiedades de margen (margin) y padding (padding).

Ejemplo:
<div style="background-color: lightblue; padding: 10px;">
  Este es un elemento de bloque.
</div>

3. Inline-block
Los elementos inline-block combinan características de los elementos inline y block. Se muestran en línea con otros elementos, pero permiten especificar propiedades de ancho y alto.

#Características:

Se muestran en línea con otros elementos (no inician una nueva línea).
Permiten especificar propiedades de ancho (width) y alto (height).
Respetan todas las propiedades de margen y padding.

Ejemplo:
<div style="background-color: lightblue; padding: 10px;">
  Este es un elemento de bloque.
</div>

3. #Inline-block
Los elementos inline-block combinan características de los elementos inline y block. Se muestran en línea con otros elementos, pero permiten especificar propiedades de ancho y alto.

#Características:

Se muestran en línea con otros elementos (no inician una nueva línea).
Permiten especificar propiedades de ancho (width) y alto (height).
Respetan todas las propiedades de margen y padding.

Ejemplo:
<span style="display: inline-block; width: 100px; height: 50px; background-color: yellow;">
  Este es un elemento inline-block.
</span>
<span style="display: inline-block; width: 100px; height: 50px; background-color: orange;">
  Otro elemento inline-block.
</span>