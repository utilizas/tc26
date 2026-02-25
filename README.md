# Teoría del Conocimiento
## Monografía técnica — v.5 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.10826047.svg)](https://doi.org/10.5281/zenodo.10826047)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Monografía técnica sobre *Teoría del conocimiento*, orientada a estudiantes de 3.º y 4.º curso de Filosofía y Humanidades / Ciencias Sociales. Contextualiza el desarrollo de la teoría del conocimiento en interacción con la ciencia y la cultura contemporánea, proporcionando la base teórica para un curso posterior de epistemología aplicada.

El enfoque es interdisciplinar, centrado en metodologías de investigación y problemas de interés transversal, con especial atención a desarrollos teórico-conceptuales del siglo XXI en biología, física, evolución, ciencia cognitiva y genética.

## Despliegue

- **Vercel**: [https://tc26.vercel.app/](https://tc26.vercel.app/)
- **Netlify**: [https://tc26.netlify.app/](https://tc26.netlify.app/)

---

## Estructura de contenidos

| Cap. | Título |
|:----:|--------|
| — | **Introducción** |
| 1 | La teoría del conocimiento ante las nuevas teorías científicas |
| 2 | El conocimiento de la naturaleza física: espacio y tiempo, azar y orden |
| 3 | El conocimiento de la naturaleza biológica y su complejidad |
| 4 | La revolución cognitiva |
| 5 | El pensamiento subyacente |
| 6 | Epistemología social y convivencia democrática |
| 7 | Vectores de irracionalidad en la dinámica sociocultural |
| 8 | Universidades y dimensión social del conocimiento |
| — | **Referencias** |
| A | **Glosario** (apéndice) |

## Producción y herramientas

### Quarto / RStudio

Esta versión (TC26) ha sido producida con [Quarto](https://quarto.org/) como entorno de autoría, generando un libro HTML multipágina con las siguientes características:

- **Sistema de citas**: BibTeX, con bibliografías renderizadas en sección única al final y gestión automatizada de referencias.
- **Notas**: tooltips clicables integrados en el flujo de texto.
- **Estudios de caso y textos complementarios**: callouts plegables (`::: {.callout-note collapse="true"}`), con pestañas integradas (panel-tabsets) en algunos casos.
- **Glosario ampliado**: 137 entradas (vs. 108 en la versión de 2025), reformuladas en muchos casos.
- **Tema**: adaptado para modos claro y oscuro.
- **Navegación**: barra lateral con tabla de contenidos, búsqueda integrada, navegación por capítulos.

La configuración del proyecto se gestiona mediante `_quarto.yml`. El renderizado genera los archivos HTML estáticos en el directorio de salida.

### Despliegue en Vercel y Netlify

El repositorio se importa directamente en ambas plataformas:

- **Vercel**: importación del repositorio GitHub con el `index.html` en la carpeta principal. Despliegue automático en cada push.
- **Netlify**: configuración análoga, con despliegue continuo desde la misma rama.

No se requiere build step en ninguna de las dos plataformas, ya que el repositorio contiene los archivos HTML pre-renderizados por Quarto.

### Herramientas de búsqueda y asistencia

Como alternativas a los buscadores convencionales se han utilizado Claude Sonnet 4.5 (Anthropic), Elicit, Perplexity, Copilot y GPT-5.1, cuyos outputs han sido revisados y contrastados para detectar imprecisiones o errores en enlaces y referencias.

Los recursos de edición y gestión de notas son compatibles con herramientas como [Zettlr](https://www.zettlr.com/), [Obsidian](https://obsidian.md/), [Logseq](https://logseq.com/) y [Zotero](https://www.zotero.org/).

---

## Licencia

Esta obra está licenciada bajo [Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Usted es libre de compartir y adaptar el material bajo las siguientes condiciones:
- **Atribución** — Debe dar crédito adecuado, proporcionar un enlace a la licencia e indicar si se realizaron cambios.
- **NoComercial** — No puede utilizar el material con fines comerciales.
- **CompartirIgual** — Si remezcla, transforma o crea a partir del material, debe distribuir su contribución bajo la misma licencia.

© 2026 Miguel Moreno Muñoz  

---

## Cita sugerida y portada

> Moreno Muñoz, M. (2026). *Teoría del Conocimiento. Monografía técnica 2631137 - (v.4)*. Zenodo - CERN Research Repository. https://doi.org/10.5281/zenodo.10826047  


```plaintext
@book{moreno2026teoria,
  author       = {Moreno Muñoz, Miguel},
  title        = {Teoría del Conocimiento},
  subtitle     = {Monografía técnica 2631137 (v.4)},
  year         = {2026},
  publisher    = {Zenodo -- CERN Research Repository},
  doi          = {10.5281/zenodo.10826047},
  url          = {https://doi.org/10.5281/zenodo.10826047}
}
```

<details>
  <summary style="color: rgba(128,128,128,0.75); font-weight: 600;">Mostrar portada</summary>

![Imagen generada con Gemini 3.1](tc26cov.webp)

</details>
