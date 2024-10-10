# Dorks

## Filtros

- `allintext:` Busca las palabras exactas en el texto de la página.
- `intext:` Busca el conjunto de palabras o palabras aisladas.
- `inurl:` Busca las palabras en la URL de la página.
- `allinurl:` Busca las palabras exactas en la URL de la página.
- `intitle:` Busca las palabras en la etiqueta del título de la página.
- `allintitle:` Busca las palabras exactas en la etiqueta del título de la página.
- `site:` Busca las palabras en un sitio web específico.
- `filetype:` Busca archivos con una extensión específica.
- `link:` Busca páginas que enlazan a la URL especificada.
- `allinanchor:` Busca páginas con urls apuntando a la URL especificada.
- `related:` Busca páginas relacionadas con la URL especificada.
- `cache:` Muestra la versión que Google tiene en caché.

## Operadores

### Busqueda literal

Este operador busca la frase exacta que se le pase entre comillas.

```
"frase exacta"
```

Es útil si la frase puede dar lugar a resultados con ruido o si sabemos que la frase exacta es la que queremos encontrar.

### OR

Este operador busca por un término o por otro.

```
site:example.com OR site:example.org
```

### AND

Busca ambos términos.

```
site:example.com AND site:example.org
```

### Incluir

Ordena los resultados segun el numero de ocurrencias encontradas

```
site:example.com +site:example.org
```

### Excluir

Excluye los resultados que contengan el término.

```
site:example.* -site:example.org
```

### Patron global (*)

Sustituye esto por cualquier cosa.

```
site:example.*
```