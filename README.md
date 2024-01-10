# Genealogía de la soberbia intelectual

## ¿Qué es este repositorio?

Este repositorio contiene el código fuente del libro "Genealogía de la soberbia intelectual", escrito por Enrique Serna en formato ePub.

## ¿Cómo compilar el libro?

Para compilar el libro, ejecute el siguiente comando:

```bash
zip -rX "../Serna, Enrique - Genealogía de la soberbia intelectual.epub" mimetype $(ls|xargs echo|sed 's/mimetype//g') -x \*.DS_Store -x \*.git\*
```

El comando anterior generará un archivo llamado _Serna, Enrique - Genealogía de la soberbia intelectual.epub_ en el directorio padre del repositorio.
