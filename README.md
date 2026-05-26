# Xournal++ - Vibe

This is a personal fork of the [Xournal++](https://github.com/xournalpp/xournalpp) project.

**Purpose**: The sole purpose of this repository is to add an "auto breakline" (automatic word wrap) feature to the text boxes in Xournal++. It is intended for personal use.

## Credits

All credit for the main application goes to the incredible [Xournal++ team and contributors](https://github.com/xournalpp/xournalpp). 

Xournal++ is a hand note-taking software written in C++ with the target of flexibility, functionality and speed.

For official features, installation instructions, and contributing guidelines, please refer to the [official repository](https://github.com/xournalpp/xournalpp).

---

## About Xournal++

Xournal++ (/ˌzɚnl̟ˌplʌsˈplʌs/) is a hand note-taking software written in C++ with the target of flexibility, functionality and speed.
Stroke recognizer and other parts are based on Xournal Code, which you can find at [SourceForge](http://sourceforge.net/projects/xournal/).

Xournal++ features:
- Supports pressure-sensitive styluses and digital pen tables
- Paper backgrounds for note-taking, scratch paper, or whiteboarding
- Annotate on top of PDFs
- Text tool for adding text in different fonts, colors, and sizes (**enhanced in this fork with auto breakline!**)
- And many more! See the [official guide](https://xournalpp.github.io/guide/overview/).

## Cambios y características principales de este fork (Xournal++ Vibe)

- **Auto breakline** (ajuste automático de línea en texto).
- **Invertir Colores (Ctrl+I)** interactivo en el lienzo, trazos, cajas de texto, LaTeX, miniaturas y fondo.
- **Fechas** integradas en el documento visual y en el formato XML.
- **Navegación y vista:** Autoscroll mientras se escribe y opción para hacer scroll a la última anotación.
- **Mejoras Pango/LaTeX:** Soporte de Pango HTML markup, traducción de LaTeX a Pango HTML, y reemplazo de símbolos LaTeX por Unicode en cajas de texto. Modificación de tamaños e interlineado.
- **Exportación:** Exportación a PDF mediante script de Python (con y sin fondo).
