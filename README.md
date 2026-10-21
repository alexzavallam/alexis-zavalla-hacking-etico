# Alexis Zavalla — Hacking ético

Homepage brutalista para consultoría de hacking ético. Un solo archivo (`index.html`), sin dependencias ni build. Usa Google Fonts (Archivo Black y Space Mono).

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `hacking-etico`).
2. Sube estos archivos a la raíz del repo.
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
5. Guarda. En uno o dos minutos quedará en `https://TU-USUARIO.github.io/hacking-etico/`.

### Con la terminal

```bash
cd alexis-zavalla-hacking-etico
git init -b main
git add .
git commit -m "Homepage inicial"
git remote add origin https://github.com/TU-USUARIO/hacking-etico.git
git push -u origin main
```

## Qué editar

- Correo de contacto: busca `mailto:` en `index.html`.
- Casos y servicios: son ejemplos. Reemplázalos por trabajos reales.
- Colores: variables al inicio del `<style>` (`--blue`, `--orange`, `--paper`, `--ink`).
