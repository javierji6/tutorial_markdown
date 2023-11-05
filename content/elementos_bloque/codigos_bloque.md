+++
title = "Códigos de Bloque"
weight = 5
+++

Los bloques de código son una parte de Markdown, ya que permiten mostrar código.

## Bloques de Código en línea

Los bloques de código en línea se crean al rodear el texto con backticks ` `` `.

***Ejemplo:***

```markdown
`console.log('Hola Mundo!');`
```

_Se ve así:_ `console.log('Hola Mundo!');`

## Bloques de Código

Los bloques de código con varias líneas se crean al rodear el código con tres backticks ` ``` ` al inicio y al final del bloque, también se puede especificar el lenguaje seguido del los tres backticks iniciales.

***Ejemplo:***

```markdown
```javascript
function saludar() {
    console.log('¡Hola Mundo!');
}
```

_Se ve así:_

```javascript
function saludar() {
    console.log('¡Hola Mundo!');
}
```