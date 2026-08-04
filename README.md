# Teorema de Noether · Noether's Theorem

**Autor · Author:** Jhemerson Alvarado
· [![ORCID](https://img.shields.io/badge/ORCID-0009--0004--8141--3241-a6ce39?logo=orcid&logoColor=white)](https://orcid.org/0009-0004-8141-3241)
**Institución · Institution:** Universidad Nacional Mayor de San Marcos, Lima – Perú
**Fecha · Date:** Febrero 2024 · February 2024

🇪🇸 [Español](#español) · 🇬🇧 [English](#english)

---

## Español

Artículo que aborda la derivación del **Teorema de Noether** a través del
**Principio de Acción Estacionaria**, siguiendo una estructura similar a la de la
teoría de campos clásica y enfatizando las propiedades de invariancia de la
acción. Incluye además una exposición de la biografía de Emmy Noether.

### Contenido

- **Introducción**
- **Historia y antecedentes** — vida de Amalie Emmy Noether y los Teoremas de Noether
- **Teorema de Noether** — la acción, transformaciones de simetría noetherianas y leyes de conservación
- **Ejemplo**
- **Discusiones**

**Palabras clave:** Principio de Acción Mínima, Leyes de conservación, Lagrangiano, Invariancia.

### Compilación

El documento usa figuras en formato EPS, por lo que requiere compilar con
`-shell-escape` (para la conversión automática vía `epstopdf`).

```bash
latexmk -pdf -shell-escape main.tex   # recomendado
latexmk -c                            # limpiar archivos auxiliares
```

### Licencia

Este trabajo se comparte, como parte de un portafolio de redacción científica,
bajo la licencia
[Creative Commons Atribución-NoComercial-SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)](LICENSE).
Puedes compartir el material citando adecuadamente al autor, pero no está
permitido modificarlo ni usarlo con fines comerciales.

---

## English

Article addressing the derivation of **Noether's Theorem** through the
**Principle of Stationary Action**, following a structure similar to that of
classical field theory and emphasizing the invariance properties of the action.
It also includes an exposition of Emmy Noether's biography.

### Contents

- **Introduction**
- **History and background** — life of Amalie Emmy Noether and the Noether Theorems
- **Noether's Theorem** — the action, Noetherian symmetry transformations and conservation laws
- **Example**
- **Discussion**

**Keywords:** Least action principle, Conservation laws, Lagrangian, Invariance.

### Building the document

The document uses EPS figures, so it must be compiled with `-shell-escape`
(for automatic conversion via `epstopdf`).

```bash
latexmk -pdf -shell-escape main.tex   # recommended
latexmk -c                            # clean auxiliary files
```

### License

This work is shared, as part of a scientific-writing portfolio, under the
[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](LICENSE)
license. You may share the material with proper attribution, but you may not
modify it or use it for commercial purposes.

---

## Estructura · Repository structure

```
github_Noether/
├── main.tex        # Fuente LaTeX · LaTeX source
├── main.pdf        # Documento compilado · Compiled document
├── figuras/        # Imágenes · Figures (.eps, .png)
├── LICENSE         # Licencia · License (CC BY-NC-ND 4.0)
└── README.md
```
