# Frontend2

Frontend2 is a collection of HTML/CSS templates, Stylus sources, and examples for the Puls4 community project. It demonstrates two styling workflows—pure CSS and Stylus preprocessing—plus Bootstrap integration and utility demos.

## Directory Structure

- **css/**
  - `normalize.css`, `bootstrap.min.css` &mdash; CSS resets and framework.
  - `puls4.css`, `puls4_2.css`, `grid.css` &mdash; compiled stylesheet outputs.
  - `puls4.styl`, `puls4_2.styl`, `grid.styl` &mdash; Stylus source files.
- **ejercicios/**
  - `menuCss3.html` &mdash; CSS3 breadcrumb menu demo (uses Prefixfree).
- **fonts/**
  Custom icon font files for menu and icons.
- **imagenes/**
  Logos, avatars, and placeholder images.
- Root HTML files:
  - `index.html` &mdash; Default Puls4 template with `normalize.css` + `puls4.css`.
  - `mockup.html` &mdash; Bootstrap-based layout using `bootstrap.min.css` + `puls4_2.css`.
  - `grid.html` &mdash; Grid system example combining Bootstrap grid and `grid.css`.
  - `pruebaGlobo.html` &mdash; Speech balloon CSS demo.

## Getting Started

1. Clone or download this repo.
2. To view any example, open the corresponding `.html` file in your browser.
3. **Compile Stylus sources (optional):**
   ```bash
   stylus css/puls4.styl   -o css/puls4.css
   stylus css/puls4_2.styl -o css/puls4_2.css
   stylus css/grid.styl    -o css/grid.css
   ```
4. Ensure the `fonts/` and `imagenes/` folders remain in place so icons and images load correctly.

## Dependencies

- Stylus CLI (for preprocessing `.styl` files).
- A modern browser with support for CSS3 and web fonts.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.