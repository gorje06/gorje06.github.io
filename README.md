# Personal Site — Link in Bio

Página personal estilo cybersecurity. Un solo archivo, sin dependencias.

## Vista previa local

Abre `index.html` en tu navegador (doble clic), o:

```powershell
cd "personal-site"
python -m http.server 8080
```

Luego visita: http://localhost:8080

## Personalizar

Edita la sección `CONFIG` al final de `index.html`:

- `username` — nombre que aparece grande
- `githubUser` — tu usuario de GitHub (también carga la foto de perfil)
- `badges` — etiquetas tipo `PENTESTER`, `BLUE TEAM`
- `links` — array con tus URLs (GitHub, LinkedIn, HTB, etc.)

## Publicar en GitHub Pages (gratis)

1. Crea un repo en GitHub llamado `gorje06.github.io`
2. Sube todo a la rama `main`:
   - `index.html`
   - `banner.jpg`
   - `toast-deco.png`
   - `plate-effect-loop.png`
   - carpeta `gifs/` (gifs de animales)
3. Ve a **Settings → Pages → Source: main**
4. En ~2 minutos estará en: `https://gorje06.github.io`

## Dominio gratis (opcional)

1. Registra `tunombre.dpdns.org` en [DigitalPlat](https://domain.digitalplat.org/)
2. En DNS, agrega CNAME: `@` → `TU_USUARIO.github.io`
3. En GitHub Pages → **Custom domain** → `tunombre.dpdns.org`

## Dominio .com (opcional, ~$10/año)

Compra en Cloudflare/Namecheap y apunta CNAME a `TU_USUARIO.github.io`.
