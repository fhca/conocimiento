---
aliases:
tags:
  - MoC
URL:
Temas:
Número de página:
Creación de nota: 20250802
rank: 1
---

```dataview
TABLE WITHOUT ID
 file.link AS "Nota", file.mtime AS "Actualizado", length(file.inlinks) AS "Ligas entrantes"
 FROM #átomo SORT file.mtime DESC
 LIMIT 20
```
