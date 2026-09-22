# MiGente - Biblioteca de Autores
Blog original: José Altimiras Lampre

Estructura jerárquica real rescatada:
Cada <entry> del Atom = 1 AUTOR (entry.title = nombre del autor)
Dentro del <content> = todas sus obras con Título + Link de descarga.

Este ZIP contiene:
- index.html  → sitio listo con sidebar A-Z de autores, buscador global, cards de obras
- posts.json  → [{ autor, obras: [{titulo, link, fecha}] }] estructura jerárquica
- authors.json → [{ autor, count }] plano para facilitar índices
- README.md   → este archivo

Publicación en GitHub Pages:
1. Crea repo: migente-biblioteca
2. Sube index.html (y opcional posts.json/authors.json) a main
3. Settings > Pages > Source: Deploy from a branch / main / root
4. https://tu-usuario.github.io/migente-biblioteca/

Todo offline, sin backend. 100% estático.
Total: 101 autores, 828 obras.
