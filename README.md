# Proyecciones SVG · sitio web

Landing en español con ejemplos vectoriales interactivos, instalación asistida y por terminal, peticiones para Codex, formatos de salida, límites y preguntas frecuentes.

**Sitio:** https://mauricioperera.github.io/proyecciones-svg-site/

Este repositorio contiene únicamente la página estática y ejemplos ilustrativos. La skill y su release 1.1.0 son públicas en [MauricioPerera/proyecciones-svg](https://github.com/MauricioPerera/proyecciones-svg). La landing ofrece enlaces directos al ZIP, al instalador Python y a las sumas SHA-256, sin iniciar sesión. Sus cuatro ejemplos incluyen la descarga opcional del volumen en formato Cota 1.0.0, además de las tres vistas y el giro SVG.

## Vista previa local

```sh
python -m http.server 8770 --bind 127.0.0.1 --directory docs
```

Abre http://127.0.0.1:8770/. No se necesitan dependencias ni compilación. GitHub Pages publica desde `main`, carpeta `/docs`.

La fuente canónica de la landing y el programa de generación de sus ejemplos se mantienen junto a la skill en su repositorio público. Esta copia del sitio no necesita incluir el generador Python.

Licencia MIT. © 2026 Mauricio Perera.
