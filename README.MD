# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2 
===========

# Formatos de énfasis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, formato normal.
- Aqui podemos usar formato *itálica*, pero también **bold** y ~~tachado~~.

# Lista de la lista ordenadas
1. Esto es un item de la lista ordenada.
2. Esto es un item de la lista ordenada.
3. Esto es un item de la lista ordenada.
- Esto es un item de la lista desordenada.
- Esto es un item de la lista desordenada.
- Esto es un item de la lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo GitHub](https://pngimg.com/uploads/github/github_PNG40.png)

# Code Snippets
Código en Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas 
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| César  | Bárcenas | 2016300139| 
|Marielena| Carmona | 2516310558|

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Líneas divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___

# Saltos de línea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista