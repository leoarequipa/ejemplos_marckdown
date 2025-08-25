# Ejemplo 1: Básico - Formato de texto

```markdown
# Título Principal

Este es un **texto en negrita** y este es un *texto en cursiva*.

- Elemento de lista 1
- Elemento de lista 2
```

**Explicación:**
- `#` crea un título grande.
- `**texto**` pone el texto en negrita.
- `*texto*` pone el texto en cursiva.
- `-` crea una lista con viñetas.

---

# Ejemplo 2: Intermedio - Enlaces, imágenes y tablas

```markdown
## Enlaces e Imágenes

[Visita GitHub](https://github.com)

![Logo de Markdown](https://markdown-here.com/img/icon256.png)

| Nombre   | Edad |
|----------|------|
| Ana      | 23   |
| Bernardo | 31   |
```

**Explicación:**
- `[texto](url)` crea un enlace.
- `![alt](url)` inserta una imagen.
- Las tablas se crean usando `|` y `-` para separar columnas y filas.

---

# Ejemplo 3: Avanzado - Código, citas y listas anidadas

```markdown
### Código y Citas

> "Markdown es fácil de usar."  
> — Usuario

```python
def saludar(nombre):
    print(f"Hola, {nombre}!")
```

1. Primer paso
   - Subpaso A
   - Subpaso B
2. Segundo paso
```

**Explicación:**
- `>` crea una cita.
- Tres acentos invertidos (```) indican un bloque de código.
- Las listas numeradas pueden tener sublistas con guiones.
