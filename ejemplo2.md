# Comandos y Sentencias Soportadas por Markdown

Markdown es un lenguaje de marcado ligero. Aquí tienes los elementos principales que soporta, con ejemplos y explicación:

## Encabezados

Usa `#` para crear títulos:

```markdown
# Título 1
## Título 2
### Título 3
```

## Énfasis

- **Negrita:** `**texto**` o `__texto__`
- *Cursiva:* `*texto*` o `_texto_`
- ~~Tachado:~~ `~~texto~~`

## Listas

- **Listas no ordenadas:**  
    `- Elemento` o `* Elemento`
- **Listas ordenadas:**  
    `1. Elemento`

## Citas

> Usa `>` para citas.

## Código

- **En línea:** `` `código` ``
- **Bloques:**  
    <pre>
    ```
    código
    ```
    </pre>

## Enlaces

- `[texto](url)`

## Imágenes

- `![alt](url)`

## Separadores

- `---` o `***` o `___`

## Tablas

```markdown
| Columna 1 | Columna 2 |
|-----------|-----------|
| Dato 1    | Dato 2    |
```

## Listas de tareas

- `[ ] Tarea pendiente`
- `[x] Tarea completada`

## Saltos de línea

Termina una línea con dos espacios o usa `<br>`.

---

**Nota:** Algunas funciones avanzadas (tablas, listas de tareas) pueden no estar soportadas en todos los visores de Markdown.

## Comandos adicionales

### Tablas avanzadas

Puedes alinear el texto en las columnas usando dos puntos:

```markdown
| Izquierda | Centro   | Derecha  |
|:----------|:--------:|---------:|
| Texto 1   | Texto 2  | Texto 3  |
```

### Listas de tareas

Puedes crear listas de tareas con casillas de verificación:

```markdown
- [ ] Elemento pendiente
- [x] Elemento completado
```

### Definiciones

Algunos visores soportan listas de definiciones:

```markdown
Término 1
:   Definición del término 1

Término 2
:   Definición del término 2
```

### Comentarios

Puedes agregar comentarios que no se muestran en el renderizado:

```markdown
<!-- Esto es un comentario -->
```

### Referencias de enlaces

Puedes definir enlaces al final del documento y referenciarlos:

```markdown
[Google][1]

[1]: https://www.google.com/
```