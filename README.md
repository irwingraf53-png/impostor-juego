# impostor-juego

## Cómo abrir el juego en la computadora
1. Asegúrate de que el archivo se llame **`index.html`** (no `index.html.txt`).
2. Haz doble clic para abrirlo en tu navegador.

### Si ves el código en pantalla (CSS/JS como texto)
Eso pasa cuando el archivo no se guarda como HTML o tiene texto extra antes del `<!doctype html>`.
Comprueba lo siguiente:
- Que el archivo **empiece exactamente** con `<!doctype html>` en la primera línea.
- Que no hayas pegado comandos de terminal o diffs dentro del archivo.
- Que el archivo tenga la extensión **.html**.

## Opción con servidor local (opcional)
Si quieres abrirlo como sitio web local, puedes usar:
```bash
python -m http.server
```
y luego abrir `http://localhost:8000` en el navegador.
