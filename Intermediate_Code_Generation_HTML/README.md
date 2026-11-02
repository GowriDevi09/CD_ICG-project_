# Intermediate Code Generation System — HTML Version

A browser-based conversion of the supplied Python mini compiler. It generates Three Address Code (TAC) for assignments, arithmetic expressions, Boolean expressions, if/else, while, and for statements.

## Run
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Enter source code or choose one of the sample buttons.
4. Click **Generate Intermediate Code**.

No Python installation, server, or external library is required. Google Fonts are optional; the app logic works offline.

## Files
- `index.html` — interface
- `style.css` — responsive design
- `script.js` — lexer, recursive-descent parser, TAC generator

## Supported operators
Arithmetic: `+ - * / %`; relational: `< > <= >= == !=`; Boolean: `&& || !`.

This is an educational mini-language implementation, not a complete C compiler. It does not perform semantic type checking or machine-code generation.
