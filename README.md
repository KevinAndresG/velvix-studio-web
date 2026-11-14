# Velvix Studio — sitio web

Página de presentación y guía de [Velvix Studio](https://github.com/KevinAndresG/VelvixStudio), el editor de video gratis para Windows.

Es HTML estático (`index.html` + `img/`), sin build.

## Ver en local

```bash
python -m http.server 8765
```

Abrir http://localhost:8765

## Publicar con GitHub Pages

1. Sube este repo a GitHub.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Queda en `https://<usuario>.github.io/<repo>/`.

El botón **Descargar** apunta a `https://github.com/KevinAndresG/VelvixStudio/releases/latest`: hay que crear un release en el repo de la app con el `.exe` adjunto.
