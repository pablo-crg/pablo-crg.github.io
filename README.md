# pablo-crg.github.io

Este repositorio contiene mi **página personal** generada con [Quarto](https://quarto.org) y publicada mediante **GitHub Pages**.

El sitio está pensado como una breve web académica donde resumo:

- Mi actividad clínica en Oncología Médica y Dermatología.
- Las principales líneas de investigación en cáncer cutáneo y melanoma.
- Información básica de docencia y formas de contacto.

---

## Estructura del proyecto

- `_quarto.yml`  
  Configuración principal del sitio (título, navegación, opciones de formato, etc.).

- `index.qmd`  
  Página de inicio / Sobre mí.

- `research.qmd`  
  Líneas de investigación y proyectos.

- `teaching.qmd`  
  Docencia, cursos y formación.

- `contact.qmd`  
  Información de contacto y enlaces.

- `docs/`  
  Salida HTML generada por Quarto.  
  GitHub Pages publica directamente el contenido de esta carpeta.

- `.gitignore`  
  Excluye archivos locales que no deben subirse (por ejemplo `.DS_Store`, `.Rhistory`, documentos de notas, etc.).

La configuración de GitHub Pages está en:

- **Settings → Pages**  
  - Source: `Deploy from a branch`  
  - Branch: `main`  
  - Folder: `/docs`

---

## Cómo actualizar la web

1. Editar los archivos `.qmd` que correspondan (por ejemplo `index.qmd`, `research.qmd`, etc.).

2. Renderizar el sitio con Quarto:

   ```bash
   quarto render
