---
aliases: 
tags:
  - "#MOC"
---
> [!INFO] <% tp.file.title %>
> Descripción del [[MOC]].
^descripcion

```dataview
TABLE WITHOUT ID
    file.link AS Nota,
    tags AS Etiquetas
FROM
    [[#]] AND
    !"Recursos"
SORT
    length(file.inlinks) DESC,
    file.name ASC
```
^conexiones

# Referencias

> Recursos interesantes, como fuentes externas de información.
> Se ha incluido un formato de lista vacía (*bullet list*) para que sea minimalista.
> Otra opción es usar la sintaxis `[^id]` para referenciar la información exterior.

- 
- 
