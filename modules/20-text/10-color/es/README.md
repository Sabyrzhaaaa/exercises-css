Resaltar un fragmento de texto con color es una forma común de llamar la atención del usuario en una página. Diferentes banners publicitarios siempre intentan informarnos sobre increíbles descuentos o que la oferta termina hoy. También, este tipo de resaltado puede indicar información importante que debe ser leída.

Usando CSS, puedes establecer el color del texto para toda la página o para una sección. Esto se determina mediante un selector que se elija. El color en sí se establece utilizando la propiedad `color`, cuyo valor es un código de color o su alias.

En esta lección, el color se indicará en formato `HEX`, que es una representación hexadecimal del color, donde `#ffffff` representa el color blanco y `#000000` el negro. Para mayor comodidad, al final de la lección se proporciona un enlace a un portal donde puedes seleccionar cualquier color y obtener su valor en formato `HEX`. Más información sobre los modelos de color en CSS se explicará en una de las próximas lecciones.

Crearemos un párrafo y resaltaremos una palabra en él. Para hacer esto, envolveremos la palabra en una etiqueta `<span>` y le daremos una clase aleatoria, que utilizaremos para seleccionar el elemento en CSS:


```html
<p><span class="info">¡Atención!</span> Información importante</p>
```

```css
.info {
  color: #5263f3;
}
```

<div class="hexlet-basics-example my-3">
  <p class="m-0"><span style="color:#5263f3;">¡Atención!</span> Información importante</p>
</div>

Para establecer el color del texto para toda la página, puedes usar el selector `body`. La propiedad `color` es heredada, por lo que el color se establecerá para todos los elementos de texto:

```css
body {
  color: #333333;
}
```
