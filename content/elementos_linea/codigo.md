+++
title = "Código"
weight = 3
+++

En ciertos tipos de publicaciones, especialmente las de carácter técnico, es necesario presentar secciones que contienen código de otro lenguaje, atajos de teclado u otro contenido que no debe ser tratado como texto normal.

## Código en línea con `<code>`

La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas inversas (backticks). Esta representación se corresponde con la etiqueta HTML `<code>`.

***Ejemplo:***

```markdown
`Esto es una línea de código`
```

_Se ve así:_ `Esto es una línea de código`.

Esto es útil para introducir código dentro de la misma línea o párrafo, algo que no permite el siguiente método.

## Texto preformateado con `<pre>`

La otra manera de agregar código en Markdown es comenzar el párrafo con cuatro espacios en blanco. Esto se corresponde con la etiqueta HTML `<pre>`.

***Ejemplo:***

```markdown
    Esto es una línea de código
```

_Se ve así:_

    Esto es una línea de código